# k1s

Simple Kubernetes dashboard that monitors cluster resources in realtime.

Written in Python3 - forked from https://github.com/mjbright/k1spy - originally inspired by https://github.com/weibeld/k1s)

## Installation (Debian/Ubuntu)

To install k1s such that it can be invoked globally, simply run the `install.sh` script:

```bash
./install.sh
```

The script will make sure Python3 and pip are installed with `apt`. Use the flag `--apt-get` to install using `apt-get` (may be useful for automation):

```bash
./install.sh --apt-get
```

## Usage

To start the dashboard, simply run:

```bash
k1s
```

Enter `Ctrl+C` to stop the dashboard.

Hello!!!
