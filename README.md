# Handwritten Character Recognition
  
<!-- TABLE OF CONTENTS -->

  

<details  open="open">

  

<summary>Table of Contents</summary>

  

<ol>

  

<li><a  href="#about-the-project">About The Project</a></li>

  

<li><a  href="#getting-started">Getting Started</a></li>

  

<li><a  href="#dependencies">Dependencies</a></li>

  

<li><a  href="#installation">Installation</a></li>

  

</ul>

  

</li>

  

<li><a  href="#usage">Usage</a></li>

  

<li><a  href="#roadmap">Roadmap</a></li>

  

<li><a  href="#contributing">Contributing</a></li>

  

<li><a  href="#license">License</a></li>

  

<li><a  href="#authors">Authors</a></li>

  

<li><a  href="#acknowledgements">Acknowledgements</a></li>

  

</ol>

  

</details>

  

  

<!-- ABOUT THE PROJECT -->

  

## About The Project

  

  

This project recognizes characters from image data. The main dataset contains images for 10 character classes:

  

Character: a b c d e f g h $ #

  

Label: 0 1 2 3 4 5 6 7 8 9

  

The 300x300 pixel images were collected as part of the UF course EEL5840. This dataset is cleaned, processed, and used for training our custom CNN model (PandaNet) which is inspired from LeNet.

  

The data was split 90:10 and 1000 samples from cifar10 dataset were added to the test data as -1 class. The model gives an accuracy of 0.92 on this test set.

  

<!-- GETTING STARTED -->

  

## Getting Started

  

  

  

### Dependencies

  

  

Tensorflow 2.6.0

```sh
conda install tensorflow==2.6.0
```

  

* OpenCV
```sh
pip install opencv-python
```

* NumPy

```sh
pip install numpy
```

* Pandas

  

```sh
pip install pandas
```

  

* scikit_learn
```sh
pip install -U scikit-learn
```

  

* MatPlotLib
```sh
pip install matplotlib
```

  
  

### Installation

  

  

* Clone the repo

  

```sh
git clone https://github.com/EEL5840-EEE4773-Spring2022/final-project-code-and-report-probably-pandas#about-the-project
```


<!-- USAGE EXAMPLES -->

  

## Usage

  

The easy-test notebook can be used to test the model on easy-test. 'test' function in this file takes the data and labels and gives predictions from the 10 classes.
  

The hard-test notebook can be used to test the model on hard-test. 'test' function in this file takes the data and labels and gives predictions from the 10 classes or -1 if the image does not belong to any of these classes.
  

## Contributing

  

  

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

  

  

1. Fork the Project

  

2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)

  

3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)

  

4. Push to the Branch (`git push origin feature/AmazingFeature`)

  

5. Open a Pull Request

  

  

<!-- LICENSE -->

  

## License

  

  

Distributed under the MIT License. See `LICENSE` for more information.

  

  

<!-- Authors -->

  

## Authors

Shivam Bang   
Dhruv Kushwaha  
Tre’ Jeter  
Yao An Lee   

Project Link: [Handwritten Character Recognition](https://github.com/EEL5840-EEE4773-Spring2022/final-project-code-and-report-probably-pandas)

  

  

<!-- ACKNOWLEDGEMENTS -->

  

## Acknowledgements

  

  

* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)

  

  

## Thank you