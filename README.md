# ubuntu-docker-base

Docker base image for ansible provisioning using Ubuntu.
This is useful, e.g., as a base image for testing ansible roles.

## Usage

You can get the latest image generated by the docker file by using
`docker pull marvelnccr/ubuntu-docker-base`
or equivalently
`docker pull marvelnccr/ubuntu-docker-base:latest`

The `latest` tag points to the content of the `master` branch.
If you want a different tagged version, you can check out those directly.
For instance:
`docker pull marvelnccr/ubuntu-docker-base:1.0`
checks out the content of the `v1.0` tag.

## Acknowledgements
We acknowledge support from the [NCCR MARVEL](http://nccr-marvel.ch/) 
funded by the Swiss National Science Foundation and the 
EU Centre of Excellence "[MaX – Materials Design at the Exascale](http://www.max-centre.eu/)". 
(Horizon 2020 EINFRA-5, Grant No. 676598).
