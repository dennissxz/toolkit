


- Text to Speech
  - gTTS
  - xunfei



- Play sound in Mac OS
  - playsound
  - pync



- Push Notification
  - pync  



- Jupyter
  - output figures in svg format
    ```
    import matplotlib.pyplot as plt

    %matplotlib inline
    %config InlineBackend.figure_format = 'svg'
    ```

    to save:
    ```
    plt.savefig('tmp.pdf', bbox_inches='tight')
    plt.show()
    ```
