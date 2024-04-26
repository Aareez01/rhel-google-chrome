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


wget https://dl.fedoraproject.org/pub/epel/8/Everything/x86_64/Packages/c/chromium-common-123.0.6312.122-1.el8.x86_64.rpm
dnf install chromium-common-123.0.6312.122-1.el8.x86_64.rpm
wget https://dl.fedoraproject.org/pub/epel/8/Everything/x86_64/Packages/c/chromium-123.0.6312.122-1.el8.x86_64.rpm
wget http://mirror.centos.org/centos/8-stream/AppStream/x86_64/os/Packages/qt5-qtbase-5.15.3-7.el8.x86_64.rpm
dnf install qt5-qtbase-5.15.3-7.el8.x86_64.rpm
dnf install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
dnf install http://repo.okay.com.mx/centos/8/x86_64/release/okay-release-1-5.el8.noarch.rpm
dnf upgrade
dnf install qt5-qtbase --nogpgcheck
wget https://pkgs.sysadmins.ws/el8/extras/x86_64/pipewire-libs-1.0.3-1.el8.x86_64.rpm
dnf install https://pkgs.sysadmins.ws/el8/base/x86_64/raven-release-1.0.1-1.el8.noarch.rpm
dnf install http://mirror.centos.org/centos/8-stream/BaseOS/x86_64/os/Packages/libtdb-1.4.9-0.el8.x86_64.rpm
dnf install http://mirror.centos.org/centos/8-stream/AppStream/x86_64/os/Packages/sound-theme-freedesktop-0.8-9.el8.noarch.rpm
dnf install http://mirror.centos.org/centos/8-stream/AppStream/x86_64/os/Packages/libcanberra-0.30-18.el8.x86_64.rpm --nogpgcheck
dnf install https://centos.pkgs.org/8-stream/centos-appstream-x86_64/glibmm24-2.56.0-2.el8.x86_64.rpm.html
dnf install http://mirror.centos.org/centos/8-stream/AppStream/x86_64/os/Packages/glibmm24-2.56.0-2.el8.x86_64.rpm
dnf install http://mirror.centos.org/centos/8-stream/AppStream/x86_64/os/Packages/libsigc++20-2.10.0-6.el8.x86_64.rpm
dnf install http://mirror.centos.org/centos/8-stream/AppStream/x86_64/os/Packages/glibmm24-2.56.0-2.el8.x86_64.rpm
dnf install https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/libconfig-1.5-9.el8.x86_64.rpm
dnf install https://repo.almalinux.org/almalinux/8/AppStream/x86_64/os/Packages/libiec61883-1.2.0-18.el8.x86_64.rpm --nogpgcheck
dnf --enablerepo=raven-extras install pipewire-libs --nogpgcheck
dnf install https://repo.almalinux.org/almalinux/8/AppStream/x86_64/os/Packages/libcanberra-gtk3-0.30-18.el8.x86_64.rpm --nogpgcheck
dnf install https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/libdaemon-0.14-15.el8.x86_64.rpm
dnf install chromium-123.0.6312.122-1.el8.x86_64.rpm --nogpgcheck


