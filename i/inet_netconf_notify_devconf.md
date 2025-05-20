# Function: <code>inet_netconf_notify_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81792930)
Location: net/ipv4/devinet.c:1799
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81792930-ffffffff81792a78: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817ff730)
Location: net/ipv4/devinet.c:1831
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff817ff730-ffffffff817ff871: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81830690)
Location: net/ipv4/devinet.c:1831
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81830690-ffffffff818307d1: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81851b60)
Location: net/ipv4/devinet.c:1875
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81851b60-ffffffff81851c8c: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d1950)
Location: net/ipv4/devinet.c:1884
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff818d1950-ffffffff818d1a7c: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81927e50)
Location: net/ipv4/devinet.c:1894
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81927e50-ffffffff81927f77: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81957090)
Location: net/ipv4/devinet.c:2033
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81957090-ffffffff819571d7: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:2086
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff819bccb9-ffffffff819bccd4: inet_netconf_notify_devconf.cold (STB_LOCAL)
ffffffff819bbad0-ffffffff819bbc10: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f27d0)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff819f27d0-ffffffff819f290a: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ae09c0)
Location: net/ipv4/devinet.c:2087
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81ae09c0-ffffffff81ae0afa: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aed840)
Location: net/ipv4/devinet.c:2086
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81aed840-ffffffff81aed97a: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad9020)
Location: net/ipv4/devinet.c:2087
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81ad9020-ffffffff81ad915a: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b98080)
Location: net/ipv4/devinet.c:2088
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81b98080-ffffffff81b981ba: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d29e50)
Location: net/ipv4/devinet.c:2095
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81d29e50-ffffffff81d29fc8: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ef1910)
Location: net/ipv4/devinet.c:2096
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81ef1910-ffffffff81ef1a88: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f51330)
Location: net/ipv4/devinet.c:2099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81f51330-ffffffff81f51487: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff820175b0)
Location: net/ipv4/devinet.c:2130
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff820175b0-ffffffff82017707: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca8a88)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffff800010ca8a88-ffff800010ca8be8: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db5210)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_unregister
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
c0db5210-c0db538c: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbdad0)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
c000000000dbdad0-c000000000dbdcb0: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000803802)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffe000803802-ffffffe000803916: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81992570)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81992570-ffffffff819926aa: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194c030)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff8194c030-ffffffff8194c16a: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fce10)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff819fce10-ffffffff819fcf4a: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv4_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a071a0)
Location: net/ipv4/devinet.c:2081
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
**Symbols:**

```
ffffffff81a071a0-ffffffff81a072da: inet_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int event</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, type, ifindex, devconf</code> ➡️ <code>net, event, type, ifindex, devconf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
