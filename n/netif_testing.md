# Function: <code>netif_testing</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1892e)
Location: include/linux/netdevice.h:3975
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81a22ca0)
Location: include/linux/netdevice.h:3975
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a37474)
Location: include/linux/netdevice.h:3975
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff81a189de)
Location: include/linux/netdevice.h:4143
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81a23000)
Location: include/linux/netdevice.h:4143
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a39854)
Location: include/linux/netdevice.h:4143
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff819ff8ce)
Location: include/linux/netdevice.h:4273
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81a0a330)
Location: include/linux/netdevice.h:4273
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a20ab7)
Location: include/linux/netdevice.h:4273
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff81ab1b9e)
Location: include/linux/netdevice.h:4296
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81abc840)
Location: include/linux/netdevice.h:4296
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81ad4f37)
Location: include/linux/netdevice.h:4296
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff81c2ae81)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81c372d8)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81c55237)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff81dddd31)
Location: include/linux/netdevice.h:4204
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81deaab8)
Location: include/linux/netdevice.h:4204
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81e0aaf7)
Location: include/linux/netdevice.h:4204
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff81e4ec71)
Location: include/linux/netdevice.h:4263
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81e5c298)
Location: include/linux/netdevice.h:4263
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81e7de87)
Location: include/linux/netdevice.h:4263
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
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
In net/core/rtnetlink.c (ffffffff81f0db34)
Location: include/linux/netdevice.h:4339
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81f1b67e)
Location: include/linux/netdevice.h:4339
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81f3ed97)
Location: include/linux/netdevice.h:4339
Inline: True
Inline callers:
  - net/core/net-sysfs.c:testing_show
```
</details>
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
