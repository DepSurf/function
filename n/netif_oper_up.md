# Function: <code>netif_oper_up</code>

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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3209
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3436
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3390
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3436
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3465
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:3465
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b8d3)
Location: include/linux/netdevice.h:3571
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff8196e58b)
Location: include/linux/netdevice.h:3571
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aca53)
Location: include/linux/netdevice.h:3797
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff819a416a)
Location: include/linux/netdevice.h:3797
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f81d3)
Location: include/linux/netdevice.h:3818
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81a104d2)
Location: include/linux/netdevice.h:3818
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a363)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81a47212)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/core/dev.c (ffffffff819fe21c)
Location: include/linux/netdevice.h:3987
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81b37694)
Location: include/linux/netdevice.h:3987
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff819fde2c)
Location: include/linux/netdevice.h:4155
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81b463c4)
Location: include/linux/netdevice.h:4155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff819e46ec)
Location: include/linux/netdevice.h:4285
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81b342b2)
Location: include/linux/netdevice.h:4285
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff81a951cc)
Location: include/linux/netdevice.h:4308
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81bfa963)
Location: include/linux/netdevice.h:4308
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff81c0b82c)
Location: include/linux/netdevice.h:4172
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81d93d41)
Location: include/linux/netdevice.h:4172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff81dbbabc)
Location: include/linux/netdevice.h:4216
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81dddcdb)
Location: include/linux/netdevice.h:4216
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/ipv6/addrconf.c (ffffffff81f62486)
Location: include/linux/netdevice.h:4216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff81e2c24c)
Location: include/linux/netdevice.h:4275
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81e4ec1b)
Location: include/linux/netdevice.h:4275
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/ipv6/addrconf.c (ffffffff81fc226f)
Location: include/linux/netdevice.h:4275
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/core/dev.c (ffffffff81eea29f)
Location: include/linux/netdevice.h:4351
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81f0dadb)
Location: include/linux/netdevice.h:4351
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/ipv6/addrconf.c (ffffffff8208f7ed)
Location: include/linux/netdevice.h:4351
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc6cc8)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffff800010d09d50)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce2140)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (c0e101e8)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca1928)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (c000000000e348e4)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007531f8)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffe000851712)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca363)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff819e68a2)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818842a3)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff819a3662)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b363)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81a51322)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c563)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/ipv6/addrconf.c (ffffffff81a5d272)
Location: include/linux/netdevice.h:3834
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
</ul>

## Differences
