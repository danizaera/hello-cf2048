# hello-cf2048

This is [Gabriele Cirulli's 2048](https://github.com/gabrielecirulli/2048) re-packaged as a CloudFoundry application.

## IBM Cloud setup

Make sure the [IBM Cloud CLI](https://cloud.ibm.com/docs/cli?topic=cli-getting-started) is installed and working.

```shell
ibmcloud version
```

In a terminal, run
```shell
ibmcloud login
ibmcloud target --cf
ibmcloud cf install
```

## Installation

Update submodules

```shell
git submodule init
git submodule update
```

Deploy the CloundFoundry application under IBM Cloud

```shell
ibmcloud cf push {app-name}
```

then open the given URL (route) in a browser.

Enjoy!

