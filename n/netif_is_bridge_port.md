# Function: <code>netif_is_bridge_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:3908
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4149
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/netdevice.h:4149
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4202
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/netdevice.h:4202
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4333
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4575
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4601
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1b25a)
Location: include/linux/netdevice.h:4807
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4807
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1b3ea)
Location: include/linux/netdevice.h:5003
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81a9d2d3)
Location: include/linux/netdevice.h:5003
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5003
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a02403)
Location: include/linux/netdevice.h:5134
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81a8849c)
Location: include/linux/netdevice.h:5134
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab49e3)
Location: include/linux/netdevice.h:5182
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81b43c9c)
Location: include/linux/netdevice.h:5182
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5182
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2e3b5)
Location: include/linux/netdevice.h:5002
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81cd07a5)
Location: include/linux/netdevice.h:5002
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de15d5)
Location: include/linux/netdevice.h:5046
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81e90965)
Location: include/linux/netdevice.h:5046
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5046
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e52c0d)
Location: include/linux/netdevice.h:5090
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81eef0f5)
Location: include/linux/netdevice.h:5090
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5090
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f11f1d)
Location: include/linux/netdevice.h:5166
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/ipv4/route.c (ffffffff81fb3255)
Location: include/linux/netdevice.h:5166
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:5166
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
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
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:4614
Inline: True
```
</details>
</li>
</ul>

## Differences
