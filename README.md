# rhel-google-chrome

https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/liberation-serif-fonts-2.00.3-7.el8.noarch.rpm
https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/liberation-sans-fonts-2.00.3-7.el8.noarch.rpm
https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/liberation-fonts-2.00.3-7.el8.noarch.rpm
https://repo.almalinux.org/almalinux/8/AppStream/x86_64/os/Packages/xdg-utils-1.1.2-5.el8.noarch.rpm
http://mirror.centos.org/centos/7/os/x86_64/Packages/vulkan-filesystem-1.1.97.0-1.el7.noarch.rpm
https://rpmfind.net/linux/centos/8-stream/AppStream/x86_64/os/Packages/vulkan-loader-1.3.250.1-1.el8.x86_64.rpm
https://rpmfind.net/linux/centos/7.9.2009/os/x86_64/Packages/vulkan-1.1.97.0-1.el7.x86_64.rpm
https://rpmfind.net/linux/centos/8-stream/AppStream/x86_64/os/Packages/mesa-vulkan-drivers-23.1.0-1.el8.x86_64.rpm



dnf upgrade --refresh rpm glibc &&     curl https://dl.google.com/linux/linux_signing_key.pub -O && rpm --import linux_signing_key.pub &&     curl https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm -O && rpm --checksig -v google-chrome-stable_current_x86_64.rpm &&     dnf install -y google-chrome-stable_current_x86_64.rpm &&     rm -rfv /etc/pki/entitlement &&     rm -fv google-chrome-stable_current_x86_64.rpm &&     rm -fv linux_signing_key.pub
