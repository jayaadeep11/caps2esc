## caps2esc (tap=esc, hold=ctrl)

01. install via pacman

```
sudo pacman -S interception-caps2esc
```

02. Copy udevmon.yaml to /etc/interception/udevmon.yaml 

```
cd caps2esc
sudo cp undevmon.yaml /etc/interception/udevmon.yaml
```

03. Enable and start udevmon:

```
sudo systemctl enable udevmon
sudo systemctl start udevmon
```



