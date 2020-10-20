# tinyML-with-TensorFlow-Lite

Reference: https://www.tensorflow.org/lite/microcontrollers

The following steps are required to deploy and run a TensorFlow model on a microcontroller:

    Train a model:
        Generate a small TensorFlow model that can fit your target device and contains supported operations.
        Convert to a TensorFlow Lite model using the TensorFlow Lite converter.
        Convert to a C byte array using standard tools to store it in a read-only program memory on device.
    Run inference on device using the C++ library and process the results.
