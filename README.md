# Common chart

This is a common [helm] chart used for building more elaborate and specific charts more easily.
It also includes a chart repository served out of the [docs/] folder and available at
[https://chrisbuchholz.github.io/common-chart/](https://chrisbuchholz.github.io/common-chart/).

[helm]: https://helm.sh
[docs/]: https://github.com/ChrisBuchholz/common-chart/tree/master/docs

The purpose of this chart and chart repository is as a training ground for me to build knowledge.

_Inspiration for this project grew from seeing what [@technosophos] was doing with his [common-chart]._

[@technosophos]: https://github.com/technosophos
[common-chart]: https://github.com/technosophos/common-chart

## Usage

Register the repository:

```
$ helm repo add common https://chrisbuchholz.github.io/common-chart/
```

Include the common chart as a subchart:

```console
$ cd mychart/charts
$ helm fetch common/common
```
