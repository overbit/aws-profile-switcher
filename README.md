# Switch
========

AWS Profile selector to switch between different profiles in the locally stored config file (`~/.aws/config`) and credential file. The chosen profile is made the default so you can use the aws cli and/or the aws sdk without specifying profile.

![](logo.png)

## Requirements

* [nodejs](https://nodejs.org/en/)

## Install
```shell
    git clone <repo>
    cd switcher
    npm install -g
```

## Usage
```shell
    switch
```

This will list all your current profiles from the config file located at `~/.aws/config` or the [non-default location](https://docs.aws.amazon.com/credref/latest/refdocs/file-location.html) of the same , choose one to make it the current default :

![](screenshot.png)

Credits
========

Initially based on the [ivarrian](https://github.com/ivarrian/switcher) project. 
