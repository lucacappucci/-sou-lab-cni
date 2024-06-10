# sou-lab-cni
Scopo del documento:
Descrivere gli step volti all'implementazione di un esercizio di laboratorio propedeutico al colloquio tecnico con Sourcesense per l'area CNI (Cloud Native Infrastructure).
Studio di Bash, Vagrant, Ansible, Prometheus, Grafana, Haproxy


- <a href="https://github.com/lucacappucci/-sou-lab-cni/blob/main/Vagrantfile">Vagrant File</a>
- <a href="https://github.com/lucacappucci/-sou-lab-cni/blob/main/deploy.yml">deploy.yml</a>
- <a href="https://github.com/lucacappucci/-sou-lab-cni/blob/main/inventory.ini">inventory.ini</a> definizione host
- <a href="https://github.com/lucacappucci/sou-lab-cni/tree/main/roles/sou_podman">sou_podman</a> ruolo ansible
  - <a href="https://github.com/lucacappucci/sou-lab-cni/blob/main/roles/sou_podman/tasks">task</a>
    - <a href="https://github.com/lucacappucci/sou-lab-cni/blob/main/roles/sou_podman/tasks/main.yml">main.yml</a> i task richiesti dall' esercizio
  - <a href="https://github.com/lucacappucci/sou-lab-cni/tree/main/roles/sou_podman/templates">templates_directory</a> i file template ansible
