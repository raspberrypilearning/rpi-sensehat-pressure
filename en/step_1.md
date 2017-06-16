- In a Python file, enter the following code:

    ```python
    from sense_hat import SenseHat

    sense = SenseHat()
    sense.clear()

    pressure = sense.get_pressure()
    print(pressure)
    ```

    <iframe src="https://trinket.io/embed/python/a70fc2a0df" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

- When you run the program, you should see something like this:

    ```bash
    1013.40380859
    ```
