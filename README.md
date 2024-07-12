# 🌊 AI-Driven Analysis of Water Treatment Sensor Data

This project uses multiple machine-learning algorithms to analyze the impact of physical and cyber attacks on a water treatment system.

## 🗃️ Datasets

## 🧠 AI Models

## 📊 Results

## 🛠 Installation

This section is dedicated to the installation of the project.

### Python Environement

Creating a virtual environement

```sh
python3 -m venv .venv
```

Installing the dependencies

```sh
source .venv/bin/activate

pip install -r requirements.txt
```

### Datasets

Creating a directory for the datasets

```sh
mkdir -p ./data
```

Installing the necessary libriaries for the installation and extraction

```sh
# For Debian / Ubuntu
sudo apt-get update && sudo apt-get install -y wget gzip
```

Go to the dedicated folder in order to donwload the different datasets

```sh
cd ./data
```

#### HAI 20.07

In order to fetch and unzip the files of the HAI dataset, run the following commands :

```sh
wget -v https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/test1.csv.gz
wget -v https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/test2.csv.gz
wget -v https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/train1.csv.gz
wget -v https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/train2.csv.gz
```

For unzipping the files :

```sh
gunzip *.gz
```

## 🧑‍💻 Usage

## 🤝 Contribution

- [Nino Lalanne-Tisné](https://github.com/ninolt)

## 📜 License

This project is licensed under the [MIT license](/LICENSE).

### Datasets

- The [HAI](https://github.com/icsdataset/hai) dataset is licensed under a [Creative Commons Attribution-ShareAlike License (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/). 
- You can access the terms of usage of the SWaT dataset [here](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/).