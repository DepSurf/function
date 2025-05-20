# Function: <code>inet6_valid_dump_ifaddr_req</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199b9a0)
Location: net/ipv6/addrconf.c:5027
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8199b9a0-ffffffff8199bb09: inet6_valid_dump_ifaddr_req.isra.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a080a0)
Location: net/ipv6/addrconf.c:5063
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a080a0-ffffffff81a08212: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3ec10)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a3ec10-ffffffff81a3ed82: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b34190)
Location: net/ipv6/addrconf.c:5109
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81b34190-ffffffff81b34300: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b42da0)
Location: net/ipv6/addrconf.c:5140
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81b42da0-ffffffff81b42f10: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b30fd0)
Location: net/ipv6/addrconf.c:5147
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81b30fd0-ffffffff81b3118f: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_valid_dump_ifaddr_req(const struct nlmsghdr *nlh, struct inet6_fill_args *fillargs, struct net **tgt_net, struct sock *sk, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf74f0)
Location: net/ipv6/addrconf.c:5185
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81bf74f0-ffffffff81bf76ec: inet6_valid_dump_ifaddr_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d90720)
Location: net/ipv6/addrconf.c:5202
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81d90720-ffffffff81d9093c: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5ece0)
Location: net/ipv6/addrconf.c:5215
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81f5ece0-ffffffff81f5eefc: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbe9c0)
Location: net/ipv6/addrconf.c:5221
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81fbe9c0-ffffffff81fbebdc: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208be50)
Location: net/ipv6/addrconf.c:5276
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8208be50-ffffffff8208c06c: inet6_valid_dump_ifaddr_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cffcd8)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffff800010cffcd8-ffff800010cffeb0: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e094e0)
Location: net/ipv6/addrconf.c:5092
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e297d0)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
c000000000e297d0-c000000000e29a5c: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084a37c)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffe00084a37c-ffffffe00084a4cc: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819de2a0)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819de2a0-ffffffff819de412: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199b060)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8199b060-ffffffff8199b1d2: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a48d20)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a48d20-ffffffff81a48e92: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a54ea0)
Location: net/ipv6/addrconf.c:5092
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a54ea0-ffffffff81a55012: inet6_valid_dump_ifaddr_req.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
