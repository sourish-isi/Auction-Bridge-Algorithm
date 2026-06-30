# Auction Bridge No-Trump Bidding Algorithm

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Python version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)

## Table of Contents

- [Overview](#overview)
- [How It Works](#how-it-works)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Overview

This project implements a deterministic No-Trump bidding algorithm for
Auction Bridge and evaluates it using Monte Carlo simulation.

## How It Works

The notebook generates random bridge hands, transforms them into a suit/rank
matrix, and evaluates whether the hand satisfies the selected No-Trump bid
criteria. The result is then tested over many simulations to estimate how often
the algorithm recommends proceeding.

## Features

-   Random bridge hand generation.
-   Distribution-based bidding algorithm.
-   Automatic No Trump recommendations.

## Installation

Install `pandas` via terminal, this is the only required library

``` bash
pip install pandas
```

## Usage

Open `Auction_Bridge_NO_TRUMP_Algorithm.ipynb` in Jupyter Notebook or
JupyterLab and run all cells. It gives one the freedom to choose how many simulations you would like to perform, also it lets one choose for which no trump bid one would like to perform the simulation.
