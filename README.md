# image-difference
Image difference with OpenCV and Python

How to install locally (assuming you have git and python> = 3.7 installed):

```console
git clone https://github.com/alisonamerico/image-difference
cd image-difference
pipenv install
pipenv shell
```

To run:

```console
python image_diff.py --first images/original_01.png --second images/modified_01.png
```
![image_difference_output_01](/img-readme/image_difference_output_01.jpg)

```console
python image_diff.py --first images/original_02.png --second images/modified_02.png
```
![image_difference_output_02](/img-readme/image_difference_output_02.jpg)

```console
python image_diff.py --first images/original_03.png --second images/modified_03.png
```
![image_difference_output_03](/img-readme/image_difference_output_03.jpg)