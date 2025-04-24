# AWS CLI Rock

The AWS CLI is an open source tool built on top of the AWS SDK for Python (Boto) that provides
commands for interacting with AWS services. With minimal configuration, you can start using all of
the functionality provided by the AWS Management Console from your favorite terminal program.

## Prerequisites

Before you begin, ensure you have the required dependencies to build rocks using Rockcraft. For this, you'll need Rockcraft installed on your machine. Follow the official installation guide [here](https://documentation.ubuntu.com/rockcraft/en/latest/how-to/get-started/).

```bash
sudo snap install rockcraft --classic
```

## Building the Rock

To build your rock, simply run the following command from the directory containing a `rockcraft.yaml` file

```bash
rockcraft pack
```
