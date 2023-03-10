# 100DaysOfHomeLab
Twitter: #100DaysOfHomeLab

- [X] Day 001 - onprem Confluence upgrade to 7.18.1 [Critical security issue](https://confluence.atlassian.com/doc/confluence-security-advisory-2022-06-02-1130377146.html)

- [X] Day 002 - Updating server via ansible
- [X] Day 003 - creating VM and installing + configuring OS for [pi-hole](https://pi-hole.net/)
- [X] Day 004 - pi-HOLE installed

**Installation**

<p><img alt="pi-hole" src="images/pi-hole-install.png"></p>

**admin web page**

<p><img alt="pi-hole" src="images/pi-hole.png"></p>

- [X] Day 005 - Backing up wife's computer before re-installation, thanks to Veeam agent

<p><img alt="veeam" src="images/wifes-PC-restore-veeam.jpg"></p>

- [X] Day 006 - My new additional storage server will be using BTRFS so time to learn something about it https://www.youtube.com/watch?v=RPO-fS6HQbY
- [x] Day 007 - Preparing new storage server - 8x8TB HDD + 6x1.6TB Enterprise SSD. 64GB RAM, 2x 10Gbit NI
- [X] Day 008 - Maintenance on old storage server. Added 18TB disk to old storage server. Just to do backup of backups before migration to new storage :) And of course I have another copy in the Cloud (S3 immutable storage). 
- [X] Day 009 - I resuscitated physical server at the disaster recovery location. high temperature... faulty air-condition. 
- [X] Day 010 - home notebook upgrade - 512GB NVMe for #VMware Workstation VM's and +32GB RAM (64GB Total)
- [X] Day 011 - I spent great day  with @vmugcz members discussing not only
- [X] Day 012 - Preparing installation USB (@Windows  11, @ubuntu  22.04, @CentOS  8Stream) for #homelab new physical clients. 
- [X] Day 013 - Bring back grafana back to game

<p><img alt="grafana" src="images/grafana.png"></p>

- [X] Day 014 - Uptime Kuma implemented

<p><img alt="kuma" src="images/uptime-kuma.png"></p>

- [X] Day 015 - AWX installed and configured

<p><img alt="awx" src="images/awx.png"></p>

- [X] Day 016 - Adding more and more servers to the Check MK monitoring

<p><img alt="check" src="images/check_mk.png"></p>

- [X] Day 017 - Upgraded S3 MINIO server in homelab [bug fix](https://github.com/minio/minio/releases/tag/RELEASE.2022-06-25T15-50-16Z)

<p><img alt="s3-minio" src="images/s3-minio.png"></p>

- [X] Day 018 - Integrate runner with CI/CD into #homelab GitLab 
 
<p><img alt="gitlab-cicd" src="images/gitlab-cicd.png"></p><br>
<p><img alt="runner" src="images/runner2004.png"></p>

- [X] Day 019 - Repairing son’s notebook. There was a bad CMOS battery. More than 25 screws.

<p><img alt="notebook-cmos" src="images/notebook-cmos.png"></p>

- [X] Day 020 - Patching and updating firmware, BIOS on my notebook. And also playing with #Terraform 

<p><img alt="notebook-bios" src="images/notebook-bios.png"></p>

- [X] Day 021 - RaspberryPi based Meteostation back in game (temperature, Wind speed, Wind direction) 
  
<p><img alt="rpi-meteo" src="images/rpi-meteo.png"></p>

- [X] Day 022 - Added temporary server to #homelab to migrate data  to new storage server with less impact. As I want to reuse some disks/controllers/10gig NICs. 
- [X] Day 023 - (5.7.2022) - I Installed ESXi OS 7.0u3 onto new temporary server and configured networking. Also I configured passthrough PCIe storage controller into VM.
  
<p><img alt="pcie-passthrough" src="images/pcie-passthrough.png"></p>

- [X] Day 024 - Transcoding my video files to save space on storage by using Tdarr  - https://tdarr.io/

<p><img alt="tdarr1" src="images/tdarr1.png"></p>
<p><img alt="tdarr2" src="images/tdarr2.png"></p>

- [X] Day 025 - Moving data to temp. storage (18TB drive) to free up old storage HW. Once done reuse some "old" HW in new storage. #100DaysOfHomeLab

<p><img alt="HDD_18TB" src="images/scp-copy-to-18TB_disk.png"></p>

[comment]: <> (dovezt NUC1)

- [X] Day 026 - Unboxing my new camera Logitech Brio, USB-C hub and solar powerbank VIKING W24W. Looking forward to test it :)

<p><img alt="axagon-usb-c" src="images/axagon-usb-c-hub.jpg"></p>
<p><img alt="logitech-brio" src="images/logitech-brio-4k.jpg"></p>
<p><img alt="powerbank" src="images/powerbank-viking-w24w.jpg"></p>

- [X] Day 027 - Helping friend with networking
  
<p><img alt="networking" src="images/networking-sg1016.jpg"></p>

- [X] Day 028 - Added 2x NVMe into ESXi's hosts (Samsung_SSD_970_EVO_500GB).

<p><img alt="datastores nvme" src="images/nvme-datastores.jpg"></p>

- [X] Day 029 - Playing with "Platform 9" = Managed Kubernetes plane. Free plan offers management capabilities up to 3 clusters & 20 nodes. Note: you must provide cluster infrastructure by yourself. https://platform9.com/

<p><img alt="Platform9 k8s cluster" src="images/platform9-cluster1.png"></p>

- [X] Day 030 - Patching Tuesday :) so glad that I invest the time to some @ansible  automation. The number of servers in #homelab increasing so fast. Time to start thinking about #K8S as the main tool for #homelab services.
- [X] Day 031 - Time for #vCenter upadte 7.0.3f in #homelab https://docs.vmware.com/en/VMware-vSphere/7.0/rn/vsphere-vcenter-server-70u3f-release-notes.html
<!-- 13.7.2022 -->
<p><img alt="vcenter update 7.0.3f" src="images/vcenter-update-703f.png"></p>

- [X] Day 032 - IPAM @phpipam upgraded to 1.5.0 

<p><img alt="ipam upgrade" src="images/phpipam-upgrade.png"></p>

- [X] Day 033 - Observium https://www.observium.org/

<p><img alt="observium" src="images/observium.png"></p>

- [X] Day 034 - Build PXE server for booting over the network. For now with just one OS, but more to come :)

<p><img alt="PXE" src="images/pxe-menu.png"></p>

- [X] Day 035 - Extending PXE boot menu..   CentOS 8 and 9 Stream, Ubuntu 18.04, 22.04 LTS and VMware ESXi 7.x
<!-- 17.7.2022-->
<p><img alt="PXE extending" src="images/pxe-boot-dc5.png"></p>

- [X] Day 036 - Maintenance on wife's computer. She is running out of space again :) As usual clean "Download" folder and move photos to shared drive :)

<p><img alt="Wife runs out of space again" src="images/wife's-computer.png"></p>

- [X] Day 037 - Attend @MyVMUG Workshop - #Tanzu Community Edition Training #1 @VMwareTCE  with Jeff Butler. Here is his repo: https://github.com/jeffgbutler/TCEWorkshop

<p><img alt="Tanzu Community Edition" src="images/tanzu.png"></p>

- [X] Day 038 - Upgrading PiHole - it's soo simple.. just run "sudo pihole -up"

<p><img alt="PiHole update" src="images/pi-hole-update.png"></p>

- [X] Day 039 - Emby @embyapp  server upgraded to the latest version and purchased Premiere lifetime license.
  <!--21.7.2022 -->
  
<p><img alt="Emby Premiere" src="images/emby-premiere.png"></p>

- [X] Day 040 - Testing my son's new keyboard :) "CZC.Gaming Guardian, Kailh Red" with red linear switches.  Looks really good and he likes  it, but I prefer brown switches. :) What is your favourite keayboard with which switches?

<p><img alt="Keyboard - day" src="images/keyboard-day.png"></p><br>
<p><img alt="Keyboard at night" src="images/keyboard-night.png"></p>

- [X] Day 041 - vCenter upgrade 7.0.3g Release notes: https://docs.vmware.com/en/VMware-vSphere/7.0/rn/vsphere-vcenter-server-70u3g-release-notes.html

<p><img alt="vCenter upgrade 7.0.3g" src="images/vcenter-update-703g.png"></p><br>

- [X] Day 042 - Build my own "Speedtest" web server with LibreSpeed https://github.com/librespeed/speedtest

<p><img alt="Speedtest" src="images/speedtest.png"></p>

- [X] Day 043 - Configured <a href="https://github.com/NginxProxyManager/nginx-proxy-manager" target="_blank">Nginx proxy manager</a> to publish local services to the internet with Let's encrypt certificates 

<p><img alt="Nginx proxy manager" src="images/nginx-proxy.png"></p>
<p><img alt="Nginx proxy manager" src="images/nginx-proxy2.png"></p>


- [X] Day 044 - Added 2nd (bakcup) VPN (L2TP server) connection to #homelab over old WIFI internet connection.
- [X] Day 045 - Playing with containers - wordpress (web+mysql)

<p><img alt="containers-wordpress-mysql" src="images/container-wordpress-mysql.png"></p>

- [X] Day 046 - Continue playing with containers.. this time with @portainerio

 <p><img alt="Portainer" src="images/portainer.png"></p>

- [X] Day 047 - Labeling time...Labels are ready.. (happy sysadmin day)
<!-- 29.7.2022 -->
<p><img alt="Labels" src="images/labels.png"></p>

- [X] Day 048 - Upgrading all my mikrotik routers/AP from version 6.x to 7.4

<p><img alt="Mikrotik upgrade" src="images/mikrotik-upgrade.png"></p>

- [X] Day 049 - Playing with "Shields IO" https://shields.io/

<p><img alt="Shields IO" src="images/shields-io.png"></p>

- [X] Day 050 - WSL upgrade to Ubuntu 22.04 TLS

<p><img alt="WSL upgrade" src="images/wsl-ubuntu-2204.png"></p>

- [X] Day 051 - Visual Code in web browser - https://github.com/coder/code-server

<p><img alt="Visual code web" src="images/code-server.png"></p>

- [X] Day 052 - Preparing #homelab for NSX-T 4.0 upgrade https://docs.vmware.com/en/VMware-NSX/4.0/rn/vmware-nsx-4001-release-notes/index.html

- [X] Day 053 - GitLab update ASAP from 15.1 to 15.2.2-ee.0.el8

<p><img alt="GitLab update" src="images/gitlab-update.png"></p>

- [X] Day 054 & 055- Created #terraform script to deploy @Azure AKS cluster - source code: https://github.com/musil/azure-k8s-small-001 Before you apply you can see costs with @infracost 

<p><img alt="Azure AKS" src="images/azure-aks-cluster.png"></p>
<p><img alt="Infracost Azure AKS clsuter" src="images/azure-aks-cluster-infracost.png"></p>

- [X] Day 056 - Working on moving terraform state file of my #homlab AKS cluster from local storage to Azure Storage Account

<p><img alt="Azure AKS backend git" src="images/azure-aks-backend-git.png"></p>

- [X] Day 057 - Updated Kerio Connect (Mail) server to latest version 9.4.1 patch1
<!--8.8.2022 -->

<img alt="kerio mailserver" src="images/kerio-connect.png">

- [X] Day 058 - I just yesterday updated Kerio Connect (mail) server to the version 9.4.1 patch1 and today was released new version 9.4.2 :)

<img alt="kerio mailserver" src="images/kerio-connect2.png">

- [X] Day 059 - Added more vCPU to GitLab server and upgraded GitLab runner Ubuntu 20.04.

<img alt="GitLab runner" src="images/gitlab-runner.png">


- [X] Day 060 - Your own self hosted #homelab URL Shortener -> http://yourls.org/.

<img alt="URL Shortener" src="images/link_shortener-yourls_org.png">

- [X] Day 061 - Preparing VM with CentOS for central logging solution (logs from all Linux VM's) .. most probably GrayLog https://www.graylog.org/ .. any suggestion  of other free logging solution for #homelab?


- [X] Day 062 & 063 - I was working on installing GrayLog. Of course there were some issues "elasticsearch.service: Failed with result 'exit-code'." Due to the default restriction on /tmp "noexec" but Java wanted to execute something there. https://docs.graylog.org/v1/docs/centos

<p><img alt="GrayLog" src="images/graylog.png"></p>

- [X] Day 064 - Reconfiguring test&dev server in #homelab to send syslog messages to GrayLog

<p><img alt="GrayLog Search" src="images/graylog-search.png"></p>

- [X] Day 065 - Team Password manager was released. Time to upgrade. https://teampasswordmanager.com/blog/new-release-11-141-247/
<!-- 16.8.2022 Patching server tuesday-->

- [X] Day 066 - Monthly Windows servers patching
<p><img alt="Windows update 2022-08" src="images/windows-update-2022-08"></p>

- [X] Day 067 - Developed QR code generator. Insipred by this link https://www.knowband.com/blog/tips/generate-qr-code-using-php/ .

<p><img alt="Generate QR code" src="images/generate-qrcode-php.png"></p>

- [X] Day 068 & 069 - Patching all the windows 10 clients at home (3 desktop, 5x NTB) + driver updates. Most of the windows clients are ready to upgrade to windows 11. But still not sure if I should do the upgrade.. It's stable/ready enough for trouble free operation?

- [X] Day 070 - Upgrading Veeam Backup & Replication upgrade to 11.0.1.1261 (20220302) Cumulative Patches - Veeam KB: https://www.veeam.com/kb4245?ad=in-text-link in P20220302 are only security patches CVE-2022-26500,CVE-2022-26501,CVE-2022-26504,CVE-2022-26503

<p><img alt="Veeam cumulative patches 20220302" src="images/veeam_20220302.png"></p>

- [X] Day 071 - Patching all the linux systems in #homelab. Almost 40VM's :)

<p><img alt="Patching linux" src="images/linux-update.png"></p>

- [X] Day 072 - Increasing the number of #homelab DNS servers to a total of 4 (2 in another location) 
- [X] Day 073 - Uptime Kuma upgrated to the latest version 1.17.1 from version 1.11.3 and added new features like "TLS certificate expiry" more in release notes: https:// https://github.com/louislam/uptime-kuma/releases
<!-- 24.8.2022 -->  
<p><img alt="Upgrade Uptime Kuma" src="images/uptime-kuma-update.png"></p>

- [X] Day 074 - Upgrading GitLab to the latest version 15.3.1-ee.0.el8 #100DaysOfHomeLab

<p><img alt="GitLab update 2" src="images/gitlab-update2.png"></p>

- [X] Day 075 - Updating Team Password Manager to the latest version 11.141.247. More info: https://teampasswordmanager.com/blog/two-patches-for-11-141-247/


- [X] Day 076 - Harbor registry @project_harbor installed on top of the photon @vmwarephoton  VM in my #homelab. #100DaysOfHomeLab https://goharbor.io/ https://github.com/goharbor/harbor 

<p><img alt="Harbor registrz" src="images/harbor-registry.png"></p>

- [X] Day 077 - Upgrading VMware NSX-T 3.2 to NSX 4.0 on top of the #homelab vSphere 7.0.3. More info: https://docs.vmware.com/en/VMware-NSX/4.0/upgrade/GUID-E04242D7-EF09-4601-8906-3FA77FBB06BD.html I plan also to do a fresh install :) #100DaysOfHomeLab

<!-- nedele 28.8.2022 -->
<p><img alt="Upgrading NSX-T 3.2 to NSX 4.0" src="images/nsx-upgrade.png"></p>

- [X] Day 078 - Continue with upgrading to NSX 4.0. Edges and ESXi hosts are upgraded. Last one is NSX Manager

<p><img alt="Upgrading NSX-T Manager 3.2 to NSX 4.0" src="images/nsx-upgrade2.png"></p>

- [X] Day 079 - Upgrade to @vmwarensx 4.0 completed. Exploring new features .. especially IPv6

<p><img alt="Exploring NSX 4.0" src="images/nsx-upgrade3.png"></p>

- [X] Day 080 - To save electricity in #homelab. Testing #vSphere power management DPM. https://docs.vmware.com/en/VMware-vSphere/7.0/com.vmware.vsphere.resmgmt.doc/GUID-051ED894-10C3-4D80-AE52-A518FB973875.html #100DaysOfHomeLab

<p><img alt="vSphere 7 DPM power management" src="images/vsphere7dpm.png"></p>

- [X] Day 081 - Testing "starship" cross-shell prompt  https://starship.rs/ nice to see git repo name and branch in the prompt :) And upgraded Infracost to 0.10.11 #homelab #100DaysOfHomeLab

<p><img alt="Starship cross-shell prompt" src="images/starship-prompt.png"></p>

- [X] Day 082 - Testing CODEBEAT -> https://codebeat.co code quality tool. It's free for open source projects. #100DaysOfHomeLab

- [X] Day 083 - I just start testing #homeassistant https://www.home-assistant.io/ . And looks like I will keep it :) #100DaysOfHomeLab

<p><img alt="Home assistant" src="images/home-assistant.png"></p>

- [X] Day 084 - Giving a chance to Windows 11 at least for a 2 weeks as a VM. We will see how it works. #100DaysOfHomeLab
<!-- nedele 4.9.2022 -->

<p><img alt="Windows 11 VM" src="images/windows11vm.png"></p>

- [X] Day 085 - Updating S3 Minio #homelab https://min.io/download#/linux  #100DaysOfHomeLab
<!-- Minio update-->

- [X] Day 086 - I am giving a chance for a while to MySQL workbench as a tool for #homelab mysql database administration instead of PhpMyAdmin. #100DaysOfHomeLab https://www.mysql.com/products/workbench/

<p><img alt="MySQL Workbench" src="images/mysql-workbench.png"></p>

- [X] Day 087 - iSCSI troubleshooting between "My friend Windows server -> INETERNET <- TRUENAS" Till yesterday it works. #100DaysOfHomeLab

- [X] Day 088,89,90 - Raspberry Pi weekend. Need to prepare 2x Raspberry Pi 3B+, 1x Raspberry Pi Zero W, Raspberry Pi 4. Add cameras on the Raspberry Pi, RetroPi  #100DaysOfHomeLab

<p><img alt="Raspberry Pi weekend" src="images/raspberry_pi_weekend.png"></p>

- [X] Day 091 - After preparing Raspberry Pi over weekend. Today I have first photos :) "raspistill -v -o  picture.jpg -n -rot 180 -ex night" #100DaysOfHomeLab


- [X] Day 092,093 - Deploying and tweeking HasteBin   https://hastebin.com/about.md server https://github.com/toptal/haste-server and client https://github.com/toptal/haste-client #100DaysOfHomeLab

<p><img alt="Haste" src="images/haste-server.png"></p>

- [X] Day 093 - Installed Ubuntu VM and installed Unifi VIDEO NVR server #100DaysOfHomeLab

<p><img alt="Unifi video NVR" src="images/unifi-video.png"></p>

- [X] Day 094 - Configuring Unifi Video NVR server and adding camera. #100DaysOfHomeLab
<!--15.9.2022 -->


- [X] Day 095 - Installing Sonarr - https://sonarr.tv/ as a docker container on top of the #homelab #100DaysOfHomeLab

<p><img alt="Sonarr" src="images/sonarr.png"></p>

- [X] Day 096 - Reconfigured storage server with 2x 10Gbit intel X540 NICs. And added 18TB HDD (total ~66TB HDD + some SSD's) #100DaysOfHomeLab

<p><img alt="NearStore2 upgrade" src="images/nearstore2-upgrade.png"></p>

- [X] Day 097 - Configured iSCSI target on the storage server for my notebook and for my friend. Both LUN's will be used as backup targets.  #100DaysOfHomeLab

<p><img alt="iSCSI targetCLI" src="images/iscsi-targetcli.png"></p>

- [X] Day 098 - Created SMB share for my wife's PC backup, on #homelab storage server. #100DaysOfHomeLab

<p><img alt="SMB share config" src="images/smb-share-config.png"></p>

- [X] Day 099 - Prometheus is ready for monitoring #homelab #100DaysOfHomeLab https://prometheus.io/docs/prometheus/latest/getting_started/

<p><img alt="Prometheus" src="images/prometheus-info.png"></p>

- [X] Day 100 - Testing YouTube-dl to download videos from different sites: http://ytdl-org.github.io/youtube-dl/supportedsites.html  - Homepage:  https://youtube-dl.org/ #100DaysOfHomeLab

<p><img alt="YouTube-dl" src="images/youtube-dl.png"></p>

<!-- 21.9.2022 -->


<!-- nedele 12,13.9.2022 -->

<!-- https://github.com/Lissy93/dashy -->

<!-- patching windows & Linux

<p><img alt="" src="images/.png"></p>

Postuj i na 
- linkedIn
- Facebook
- Twitter
- Instagram
- VPXD blog
[comment]: <> (clean up VM's to save space)
[comment]: <> (Nearstore2)
patching servers tuesday after 30days 12.6,12.7,9.8,13.9
patching notebooks
Windows 11
https://www.kasmweb.com/cloud-personal
	Grocy
	Crowdsec
Prometheus
Jackett
youtube-dl
pyLoad
Radarr
Bitwarden
Machinaris
Photoprism
ipfs
netdata
beets
remmina
hammond
emulatorjs
filebrowser
miniflux
typecho
aria2
wekan
shiori
pylon
mstream
sickchill
double-take
bookstack
navidrome
endlessh
papermerge
owncast
pidio-cells
calibre
scrutiny
rsnapshot
     phpldapadmin
chevereto
https://meshcentral.com/info/
MongoDB
- Logging - syslog (grafana/loki nebo LogInsight)
- K8S cluster in HA
	- rancher
	- portainer.io
	- traefik
	- argoCD
- seafile ?
- syncthing ?
- nextcloud
- NTP
- LOADBALANCER
- Firewall HA
- Router HA


https://nip.io/
https://kind.sigs.k8s.io/
https://free-for.dev/

-->




