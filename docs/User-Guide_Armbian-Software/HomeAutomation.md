# Home Automation for control home appliances


***

## openHAB empowering the smart home
This operation will install openHAB.

**Command:** 
~~~
armbian-config --cmd HAB001
~~~

**Author:** @armbian

**Status:** Stable



***

## openHAB remove
This operation will purge openHAB.

**Command:** 
~~~
armbian-config --cmd HAB002
~~~

**Author:** @armbian

**Status:** Stable



***

## openHAB purge with data folder
This operation will purge openHAB.

**Command:** 
~~~
armbian-config --cmd HAB003
~~~

**Author:** @armbian

**Status:** Stable



***

## Home Assistant open source home automation

<!--- section image START from tools/include/images/HAS001.png --->
[![Home Assistant open source home automation](/images/HAS001.png)](#)
<!--- section image STOP from tools/include/images/HAS001.png --->


<!--- header START from tools/include/markdown/HAS001-header.md --->
Home Assistant is an open source smart home platform that allows you to connect your smart home devices like your TV, fan, cameras, thermostats, lights, and sensors. As a user, you can build intricate automation using Home Assistant's user-friendly, unified web-based user interface.

Perfect to run on any single board computer with 4 cores and at least 512Mb of memory. Armbian installation is optimised to run from SD/eMMC media, but it is recommended to use SSD.

=== "Access to the web interface"

    The web interface is accessible via port **8123**:

    - URL: `https://<your.IP>:8123`
    - Username/Password: Are set at first web interface login

=== "Directories"

    Home Assistant on Armbian runs supervised in a Docker container. This secures same functionality as stock HAOS.

    - Config directory: `/armbian/haos`

<!--- header STOP from tools/include/markdown/HAS001-header.md --->

This operation will install Home Assistant.

**Command:** 
~~~
armbian-config --cmd HAS001
~~~

**Author:** @igorpecovnik

**Status:** Preview


<!--- footer START from tools/include/markdown/HAS001-footer.md --->
|Functionality|HAOS|Armbian with HA|
|:--|:--:|:--:|
|Automations|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|Dashboards|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|Integrations|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|Add-ons|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|One-click updates|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|Backups|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|General purpose server|:x:|:white_check_mark:|
|Running on exotic hardware|:x:|:white_check_mark:|
<!--- footer STOP from tools/include/markdown/HAS001-footer.md --->



***

## Home Assistant remove
This operation will remove Home Assistant.

**Command:** 
~~~
armbian-config --cmd HAS002
~~~

**Author:** @igorpecovnik

**Status:** Preview



***

## Home Assistant purge with data folder
This operation will purge Home Assistant.

**Command:** 
~~~
armbian-config --cmd HAS003
~~~

**Author:** @igorpecovnik

**Status:** Preview



***

