# Function: <code>rtnl_register_module</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a72b0)
Location: net/core/rtnetlink.c:240
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff818a72b0-ffffffff818a72c0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ca9f0)
Location: net/core/rtnetlink.c:246
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff818ca9f0-ffffffff818caa00: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81917a60)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81917a60-ffffffff81917a70: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194a080)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8194a080-ffffffff8194a090: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a196d0)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81a196d0-ffffffff81a196e0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a198c0)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81a198c0-ffffffff81a198d0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a00800)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81a00800-ffffffff81a00810: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab2bc0)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81ab2bc0-ffffffff81ab2bd0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2be00)
Location: net/core/rtnetlink.c:278
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
```
**Symbols:**

```
ffffffff81c2be00-ffffffff81c2be22: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddee90)
Location: net/core/rtnetlink.c:279
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
```
**Symbols:**

```
ffffffff81ddee90-ffffffff81ddeeb2: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e501a0)
Location: net/core/rtnetlink.c:282
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
```
**Symbols:**

```
ffffffff81e501a0-ffffffff81e501c2: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0f250)
Location: net/core/rtnetlink.c:283
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/device.c:mctp_device_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/mctp/neigh.c:mctp_neigh_init
```
**Symbols:**

```
ffffffff81f0f250-ffffffff81f0f272: rtnl_register_module (STB_GLOBAL)
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
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bebd58)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffff800010bebd58-ffff800010bebdbc: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0489c)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
c0d0489c-c0d048d0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccf1f0)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
c000000000ccf1f0-c000000000ccf204: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076fb20)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffe00076fb20-ffffffe00076fb72: rtnl_register_module (STB_GLOBAL)
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
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ea050)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff818ea050-ffffffff818ea060: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3e90)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff818a3e90-ffffffff818a3ea0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193b080)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8193b080-ffffffff8193b090: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnl_register_module(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195c8c0)
Location: net/core/rtnetlink.c:241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8195c8c0-ffffffff8195c8d0: rtnl_register_module (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
