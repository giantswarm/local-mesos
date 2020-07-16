# local-mesos

`local-mesos` is an opinionated remix of [coreos-vagrant](https://github.com/coreos/coreos-vagrant), built as a demo of running a Mesos cluster with Marathon.

The virtual machine runs one instance of the Mesos Master and Mesos Slave, as well as a Zookeeper instance and a Marathon instance. These are all run as Docker containers, configured in the cloud-config, and using the official Mesosphere images.

Lots of love to CoreOS for providing the original project <3

## Prerequisites

- Vagrant

## Getting `local-mesos`

Clone the git repository: https://github.com/giantswarm/local-mesos.git

## Running `local-mesos`

- Clone the repository, run `vagrant up`
- Once the images have been pulled (give it a couple of minutes):
  - Mesos should be available at http://172.17.8.101:5050/
  - Marathon should be available at http://172.17.8.101:8080/

## Contact

- Mailing list: [giantswarm](https://groups.google.com/forum/!forum/giantswarm)
- Bugs: [issues](https://github.com/giantswarm/local-mesos/issues)

## Contributing & Reporting Bugs

See [CONTRIBUTING](CONTRIBUTING.md) for details on submitting patches, the contribution workflow as well as reporting bugs.

## License

PROJECT is under the Apache 2.0 license. See the [LICENSE](LICENSE) file for details.
