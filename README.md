# Pivot Lab

This lab setups multiple docker containers to practice pivoting.
Access accross the hosts is linear (i.e., host1 <-> host2 <-> host3 ...etc.)

## Prerequisites

This lab requires `docker-compose` to be installed.

## Setup & Teardown

To start the lab,

```sh
sudo ./start_lab.sh
```

To stop the lab,

```sh
sudo ./stop_lab.sh
```

## Practice

> Check out the `docker-compose.yaml` file for the IP addresses for each host (it's very easy to read).

The credentials are the same for each host:

- username: `sam`
- password: `iam`

Check out my accompanying blog post: [Pivot Chaining with SSH and SOCKS](https://oliver.nichols.page/pivot-chaining-with-ssh-and-socks/)
