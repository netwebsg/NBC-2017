```
[root@c20m ~]# cat /etc/hosts
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4
::1         localhost localhost.localdomain localhost6 localhost6.localdomain6

10.10.10.105 master c20m
10.10.10.106 node1 c20n1
10.10.10.107 node2 c20n2


[root@c20m ~]#

[root@c20n1 ~]# cat /etc/hosts
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4
::1         localhost localhost.localdomain localhost6 localhost6.localdomain6

10.10.10.105 master c20m
10.10.10.106 node1 c20n1
10.10.10.107 node2 c20n2


[root@c20n1 ~]#

[root@c20n2 ~]# cat /etc/hosts
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4
::1         localhost localhost.localdomain localhost6 localhost6.localdomain6

10.10.10.105 master c20m
10.10.10.106 node1 c20n1
10.10.10.107 node2 c20n2


[root@c20n2 ~]#

```


