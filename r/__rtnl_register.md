# Function: <code>__rtnl_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172b510)
Location: net/core/rtnetlink.c:185
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
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
```
**Symbols:**

```
ffffffff8172b510-ffffffff8172b5b7: __rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817950b0)
Location: net/core/rtnetlink.c:207
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
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
```
**Symbols:**

```
ffffffff817950b0-ffffffff81795168: __rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c2920)
Location: net/core/rtnetlink.c:207
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
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
```
**Symbols:**

```
ffffffff817c2920-ffffffff817c29d8: __rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e10d0)
Location: net/core/rtnetlink.c:209
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
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
```
**Symbols:**

```
ffffffff817e10d0-ffffffff817e1187: __rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185b840)
Location: net/core/rtnetlink.c:165
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
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
```
**Symbols:**

```
ffffffff8185b840-ffffffff8185b8e2: __rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>rtnl_calcit_func calcit</code>
</li>
</ul>
</details>
</li>
</ul>
