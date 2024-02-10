# Ansible Role: Loki

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-loki?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-loki/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-loki?style=for-the-badge)](https://github.com/ursinn-ansible/role-loki/blob/main/LICENSE)

Docker Image: https://hub.docker.com/r/grafana/loki

## Options

| Option | Default Value |
| ---- | ---- |
| system_loki_docker_volume | loki_config |
| system_loki_docker_image | docker.io/grafana/loki |
| system_loki_docker_container | loki |
| system_loki_docker_network | app-network |
| system_loki_tmp_dir | /tmp/ansible-role-loki |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-loki/blob/main/LICENSE) file for the full license text.
