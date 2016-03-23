# munin-handlersocket_latency

This is munin plugin for HandlerSocket. This plugin checks read latency.



# How to use

Set plugin.
```
git clone git@github.com:takeshiyako2/munin-handlersocket_latency.git
cp munin-handlersocket_latency/handlersocket_latency /usr/share/munin/plugins/
ln -s /usr/share/munin/plugins/handlersocket_latency /etc/munin/plugins/handlersocket_latency
chmod 775 /etc/munin/plugins/handlersocket_latency
```

Edit config file.
```
vi /etc/munin/plugin-conf.d/munin-node
[handlersocket_*]
env.host 100.100.100.100
```

Re-start munin-node.
```
service munin-node restart
```

# Link

https://github.com/DeNA/HandlerSocket-Plugin-for-MySQL

