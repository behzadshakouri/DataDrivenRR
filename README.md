# FFNWrapper for DataDrivenRR

## About

DataDrivenRR is a C++/Qt research implementation of feed-forward neural-network
wrappers for data-driven rainfall-runoff modeling. It contains single- and
multi-model structures, genetic-algorithm utilities, probability-distribution
helpers, and sample precipitation and streamflow series.

## Repository contents

- `ffnwrapper_ddrr.*` and `ffnwrapper_multi_ddrr.*`: neural-network wrappers;
- `cmodelstructure*.cpp/.h`: single- and multi-model structures;
- `GADistribution.*`, `ga.*`, and `individual.h`: genetic-algorithm tools;
- `Distribution*.cpp` and `Binary.*`: sampling and encoding utilities; and
- `Precipitation*.csv` and `flow_*.csv`: example hydrologic time series.

## Building

Open `FFNWrapper_DDRR.pro` in a compatible Qt development environment and
build the project. Review file paths, input units, train/test separation, and
random seeds before reproducing or extending an experiment.

## Status

This repository is research code rather than a packaged rainfall-runoff
application. Results require independent validation before operational use.
