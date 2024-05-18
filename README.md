# Liturgical Helm Charts

Welcome to the documentation for the [Liturgical Helm charts](https://github.com/liturgical-app/charts) project.
These Helm charts install [Liturgical components](https://github.com/liturgical-app).

## Getting started

[Helm](https://helm.sh) must be installed to use the charts in this repository.

Refer to Helm's [documentation](https://helm.sh/docs/) to get started.

## Installation

```console
helm repo add liturgical https://liturgical-app.github.io/charts/
helm repo update liturgical
```

You can then run `helm search repo liturgical` to search the charts.

## Updating

I recommend you subscribe to release notifications so you know when there are chart updates.

1. Click the arrow next to the **Watch** button in the top-right corner of the Github project
2. Click **Custom**
3. Tick **Releases**
4. Click **Apply**

There's also a great tool called [`nova`](https://github.com/FairwindsOps/nova) which
can check your installed charts for available updates.

```console
nova find --format table --show-old
```

## Contributing

Contributions are always welcome, either for new features, or bug fixes.
To contribute code, fork this repo, submit a PR, and make sure the CI tests are passing.
