Zalozenia
=========
1. Przygotuj skrypty (z wykorzystaniem Ansible), które przygotują (zainstalują oraz uruchomią) środowisko Kubernetes na trzech maszynach w postaci master node oraz dwóch worker node uwzględniając wszelkie dobre praktyki. Jako system operacyjny istniejący na maszynach można wg preferencji przyjąć Debian lub Centos.  

Zakładam, że zadanie ma na celu sprawdzenie mojej znajomości Ansible więc unikam korzystania z gotowych roli i collections.  
Dla uproszczenia pracuje na koncie roota.  

Testowane na:  
- Ansible >= 2.9  
- CentOS 7 VMs 2 CPU, 2 GB RAM, minimal install

Skonfiguruj swoje inventory host.ini i uruchom mnie z ansible-playbook -i hosts.ini site.yml  