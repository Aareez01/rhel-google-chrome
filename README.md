# rhel-google-chrome

https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/liberation-serif-fonts-2.00.3-7.el8.noarch.rpm
https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/liberation-sans-fonts-2.00.3-7.el8.noarch.rpm
https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/liberation-fonts-2.00.3-7.el8.noarch.rpm
https://repo.almalinux.org/almalinux/8/AppStream/x86_64/os/Packages/xdg-utils-1.1.2-5.el8.noarch.rpm
http://mirror.centos.org/centos/7/os/x86_64/Packages/vulkan-filesystem-1.1.97.0-1.el7.noarch.rpm
https://rpmfind.net/linux/centos/8-stream/AppStream/x86_64/os/Packages/vulkan-loader-1.3.250.1-1.el8.x86_64.rpm
https://rpmfind.net/linux/centos/7.9.2009/os/x86_64/Packages/vulkan-1.1.97.0-1.el7.x86_64.rpm
https://rpmfind.net/linux/centos/8-stream/AppStream/x86_64/os/Packages/mesa-vulkan-drivers-23.1.0-1.el8.x86_64.rpm



yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm

dnf install -y libX11 libX11-common libXau libXext libwayland-client libxcb 

https://snapcraft.io/install/chromium/rhel

https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/squashfs-tools-4.3-20.el8.x86_64.rpm

https://rpmfind.net/linux/centos/8-stream/AppStream/x86_64/os/Packages/qt5-qtbase-5.15.3-7.el8.x86_64.rpm



# Download the latest available Chrome for Testing binary corresponding to the Stable channel.
npx @puppeteer/browsers install chrome@stable

# Download a specific Chrome for Testing version.
npx @puppeteer/browsers install chrome@116.0.5793.0

# Download the latest available ChromeDriver version corresponding to the Canary channel.
npx @puppeteer/browsers install chromedriver@canary

# Download a specific ChromeDriver version.
npx @puppeteer/browsers install chromedriver@116.0.5793.0


npx @puppeteer/browsers install chromedriver@116.0.5793.0 --unsafe-perm=true --allow-root

