# run-once-ipynb
This custom cell magic command ensures that the notebook cell runs only once during the runtime or even the lifetime. If the cell has already been executed before with identical code, it will display the previous output, saving time by avoiding redundant computations.

Support every output type so far (Image, Matplotlib, Pandas DataFrame, etc.).

# Getting Started
Run this cell to register the magic cell (`%%run_once`).

![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/567bce81-5336-424d-9bbb-548f2b319de9)

# Example Usage:
## First Run (it will compute actual output):
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/0a0cb2e9-c70b-4c5a-aa35-a99812c063f0)
## Second Run (it will display history output):
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/432f5274-8f8e-48a0-be0c-9bd212ffc123)

# Another Example Usage (Image):
## First Run (it will compute actual output):
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/84de076b-70b6-4009-add7-677c306e5860)
## Second Run (it will display history output):
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/9a070094-95be-43bd-b7d3-a35a88017f32)

# Another Example Usage (Pandas DataFrame with GDrive):
## First Run (it will compute actual output):
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/8f03d6ef-46cf-4420-bc06-6efc5066e788)
## Second Run (it will display history output):
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/b67141c3-a0f0-494d-8c0e-526f405f5fca)

As you see, if you specify the argument `%%run_once` to the `drive/MyDrive/run_once`, it will store the cell code and its HTML output in Google Drive.
![image](https://github.com/wawan-ikhwan/run-once-colab/assets/72451078/ca2dcffa-56dc-4bca-910f-25c1ee528150)
