# Astolfo-grub-theme
Astolfo grub theme is cool
# Instlation Guide
Clone repository:
```
git clone https://github.com/forge-sa/Astolfo-grub-theme.git
```
Then change the grub theme in /etc/default/grub:

```
cd /etc/default
sudo nano grub
```
In /etc/default/grub uncomment GRUB_THEME:

```
GRUB_THEME="/path/to/theme.txt"
```
After that use grub-mkconfig command to apply changes

```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
Thats all, now you have a cool Astolfo theme
