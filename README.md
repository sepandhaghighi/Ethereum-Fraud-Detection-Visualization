# Data Visualization Bounty

--------------

### [Sepand Haghighi](https://github.com/sepandhaghighi) - [Farzad Ramezani](https://github.com/Farziiii)

### September 2022

--------------

## Visualization Idea

Fraud detection is a process that detects and prevents fraudsters from obtaining money or property through false means. It is a set of activities undertaken to detect and block the attempt of fraudsters from obtaining money or property fraudulently. Fraud detection is prevalent across banking, insurance, medical, government, and public sectors, as well as in law enforcement agencies. 

Our main idea in this [hackathon](https://gitcoin.co/issue/29302) is to comprehensively examine and visualize the available data related to fraud detection in the Ethereum network.

Our suggested steps to visualize data:

1. Downloading and collecting data
2. Data cleaning
3. Data statistics and distribution
4. Comparing different features of data between fraud and non-fraud classes

## Datasets

We will use two data set in this report.

1. [Ethereum Fraud Detection Dataset](https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset)
2. [Ethereum Fraud Dataset](https://www.kaggle.com/datasets/gescobero/ethereum-fraud-dataset)

We will analyze these two datasets both individually and in combination.

<div style="text-align:center;" align="center">
	<table style="text-align:center;border-collapse:collapse;">
		<th>
			<td>Number of Features</td>
			<td>Total Cases</td>
			<td>Fraud Cases</td>
			<td>Non-Fraud Cases</td>
		</th>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Detection Dataset</td>
			<td>37</td>
			<td>9816</td>
			<td>2179</td>
			<td>7637</td>
		</tr>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Dataset</td>
			<td>31</td>
			<td>12146</td>
			<td>5150</td>
			<td>6996</td>
		</tr>
		<tr>
			<td style="text-align:left;">Merged Dataset</td>
			<td>17</td>
			<td>20302</td>
			<td>5675</td>
			<td>14627</td>
		</tr>
	</table>
	<p>Table1. Datasets Overview</p>
</div>


## Requirements

1. Python >= 3.5
2. pandas >= 0.24.2
3. matplotlib >= 3.0.3
4. seaborn >= 0.9.1
5. numpy >= 1.18.5
6. notebook >= 5.7.4

- Run `pip install -r requirements.txt` or `pip3 install -r requirements.txt`

## Notebooks

<div style="text-align:center;" align="center">
	<table style="text-align:center;border-collapse:collapse;">
		<th>
			<td>GitHub Viewer</td>
			<td>NB Viewer</td>
			<td>Google Colab</td>
		</th>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Detection Dataset</td>
			<td><a href="https://github.com/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master/1.ipynb">Link</a></td>
			<td><a href="https://nbviewer.org/github/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master/1.ipynb">Link</a></td>
			<td><a href="https://colab.research.google.com/github/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master">Link</a></td>
		</tr>
		<tr>
			<td style="text-align:left;">Ethereum Fraud Dataset</td>
			<td><a href="https://github.com/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master/2.ipynb">Link</a></td>
			<td><a href="https://nbviewer.org/github/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master/2.ipynb">Link</a></td>
			<td><a href="https://colab.research.google.com/github/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master">Link</a></td>
		</tr>
		<tr>
			<td style="text-align:left;">Merged Dataset</td>
			<td><a href="https://github.com/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master/3.ipynb">Link</a></td>
			<td><a href="https://nbviewer.org/github/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master/3.ipynb">Link</a></td>
			<td><a href="https://colab.research.google.com/github/sepandhaghighi/Data-Visualization-Metamorphosis/blob/master">Link</a></td>
		</tr>
	</table>
	<p>Table2. Notebooks</p>
</div>

## Visualization Example

Here you can see a limited number of examples. The full version of this visualization and all codes can be seen in the notebooks!

<div style="text-align:center;" align="center">
<img src="images/pie1.png">
<p>Fig1. Data Distribution Pie Diagram</p>
<hr/>

<img src="images/pie2.png">
<p>Fig2. Most Received Token Type Pie Diagram (Fraud Cases)</p>
<hr/>

<img src="images/hist.png">
<p>Fig3. Received Transactions Different Statistics Comparing</p>
<hr/>

<img src="images/corr.png">
<p>Fig4. Features Correlation Diagram</p>
<hr/>

<img src="images/box.png">
<p>Fig5. Features Distribution Diagram</p>
</div>


