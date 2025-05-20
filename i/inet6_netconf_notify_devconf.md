# Function: <code>inet6_netconf_notify_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cd410)
Location: net/ipv6/addrconf.c:537
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817cd410-ffffffff817cd54f: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81839eb0)
Location: net/ipv6/addrconf.c:544
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81839eb0-ffffffff81839fda: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186b8d0)
Location: net/ipv6/addrconf.c:571
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8186b8d0-ffffffff8186b9fa: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81890310)
Location: net/ipv6/addrconf.c:582
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81890310-ffffffff81890427: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81911a60)
Location: net/ipv6/addrconf.c:582
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81911a60-ffffffff81911b77: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81968e90)
Location: net/ipv6/addrconf.c:571
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81968e90-ffffffff81968f9c: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199e770)
Location: net/ipv6/addrconf.c:569
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8199e770-ffffffff8199e87c: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a11311-ffffffff81a1132c: inet6_netconf_notify_devconf.cold (STB_LOCAL)
ffffffff81a0a8a0-ffffffff81a0a9aa: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a41550)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a41550-ffffffff81a41654: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b36ff0)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81b36ff0-ffffffff81b370f4: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b45d20)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81b45d20-ffffffff81b45e24: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b33b90)
Location: net/ipv6/addrconf.c:568
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81b33b90-ffffffff81b33c94: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfa200)
Location: net/ipv6/addrconf.c:576
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81bfa200-ffffffff81bfa304: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d935c0)
Location: net/ipv6/addrconf.c:575
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81d935c0-ffffffff81d936fe: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f61d50)
Location: net/ipv6/addrconf.c:575
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81f61d50-ffffffff81f61e8e: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc1b40)
Location: net/ipv6/addrconf.c:574
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81fc1b40-ffffffff81fc1c78: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208f0b0)
Location: net/ipv6/addrconf.c:578
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8208f0b0-ffffffff8208f1e8: inet6_netconf_notify_devconf (STB_GLOBAL)
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
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d02f70)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffff800010d02f70-ffff800010d030b4: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0a428)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
c0e0a428-c0e0a550: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2c550)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
c000000000e2c550-c000000000e2c704: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084c2d6)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffe00084c2d6-ffffffe00084c3de: inet6_netconf_notify_devconf (STB_GLOBAL)
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
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e0be0)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff819e0be0-ffffffff819e0ce4: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199d9a0)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8199d9a0-ffffffff8199daa4: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4b660)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a4b660-ffffffff81a4b764: inet6_netconf_notify_devconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net *net, int event, int type, int ifindex, struct ipv6_devconf *devconf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a575d0)
Location: net/ipv6/addrconf.c:566
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a575d0-ffffffff81a576d4: inet6_netconf_notify_devconf (STB_GLOBAL)
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
