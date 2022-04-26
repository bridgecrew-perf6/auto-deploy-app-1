## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add masterrrp https://masterrrp.github.io/auto-deploy

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
masterrrp` to see the charts.

To install the auto-deploy chart:

    helm install my-auto-deploy masterrrp/auto-deploy

To uninstall the chart:

    helm delete my-auto-deploy
    