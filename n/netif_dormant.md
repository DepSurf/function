# Function: <code>netif_dormant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713b0b)
Location: include/linux/netdevice.h:3197
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff8172a36e)
Location: include/linux/netdevice.h:3197
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff817304c7)
Location: include/linux/netdevice.h:3197
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:linkwatch_init_dev
```
```
In net/core/net-sysfs.c (ffffffff817357a8)
Location: include/linux/netdevice.h:3197
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177b90b)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81793da8)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff8179b0bd)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff817a18f8)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff817a90ab)
Location: include/linux/netdevice.h:3378
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff817c1628)
Location: include/linux/netdevice.h:3378
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff817c8e5d)
Location: include/linux/netdevice.h:3378
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff817d0218)
Location: include/linux/netdevice.h:3378
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff817c75fb)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff817dfdf1)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff817e7a0d)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff817ef938)
Location: include/linux/netdevice.h:3424
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff818411db)
Location: include/linux/netdevice.h:3453
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff8185a6c1)
Location: include/linux/netdevice.h:3453
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff8186294d)
Location: include/linux/netdevice.h:3453
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff8186aed8)
Location: include/linux/netdevice.h:3453
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff8188b8f2)
Location: include/linux/netdevice.h:3559
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff818a5f63)
Location: include/linux/netdevice.h:3559
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff818ae62d)
Location: include/linux/netdevice.h:3559
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff818bb7a8)
Location: include/linux/netdevice.h:3559
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff818aca72)
Location: include/linux/netdevice.h:3785
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff818c9513)
Location: include/linux/netdevice.h:3785
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff818d28ad)
Location: include/linux/netdevice.h:3785
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff818e2538)
Location: include/linux/netdevice.h:3785
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff818f81f2)
Location: include/linux/netdevice.h:3806
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff819164ea)
Location: include/linux/netdevice.h:3806
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff8191fbad)
Location: include/linux/netdevice.h:3806
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81931e44)
Location: include/linux/netdevice.h:3806
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff8192a382)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81948b1a)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81951ded)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81964984)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff819fe242)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81a18924)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81a22c8d)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a374c4)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff819fde52)
Location: include/linux/netdevice.h:4103
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81a189d4)
Location: include/linux/netdevice.h:4103
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81a22fed)
Location: include/linux/netdevice.h:4103
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a398a4)
Location: include/linux/netdevice.h:4103
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff819e4712)
Location: include/linux/netdevice.h:4233
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff819ff8c4)
Location: include/linux/netdevice.h:4233
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81a0a31d)
Location: include/linux/netdevice.h:4233
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a20b07)
Location: include/linux/netdevice.h:4233
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff81a951f2)
Location: include/linux/netdevice.h:4256
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81ab1b94)
Location: include/linux/netdevice.h:4256
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81abc82d)
Location: include/linux/netdevice.h:4256
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81ad4f87)
Location: include/linux/netdevice.h:4256
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff81c0b852)
Location: include/linux/netdevice.h:4120
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81c2ae78)
Location: include/linux/netdevice.h:4120
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81c372bd)
Location: include/linux/netdevice.h:4120
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81c55297)
Location: include/linux/netdevice.h:4120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:4164
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81dddd28)
Location: include/linux/netdevice.h:4164
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81deaa9d)
Location: include/linux/netdevice.h:4164
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81e0ab67)
Location: include/linux/netdevice.h:4164
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:4223
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81e4ec68)
Location: include/linux/netdevice.h:4223
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81e5c27d)
Location: include/linux/netdevice.h:4223
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81e7def7)
Location: include/linux/netdevice.h:4223
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:4299
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81f0db28)
Location: include/linux/netdevice.h:4299
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81f1b660)
Location: include/linux/netdevice.h:4299
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81f3ee07)
Location: include/linux/netdevice.h:4299
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffff800010bc6cec)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffff800010bebe04)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffff800010bf3d88)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffff800010c090b8)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (c0ce2158)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (c0d0314c)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (c0d0c3b8)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (c0d21f98)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (c000000000ca1958)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (c000000000ccd178)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (c000000000cd90dc)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (c000000000cf3c4c)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffe000753214)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffe00076e016)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffe0007753f2)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffe000786df6)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff818ca382)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff818e8aea)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff818f1dbd)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81904954)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff818842c2)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff818a292a)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff818abbed)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff818be784)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff8191b382)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff81939b1a)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff81942ded)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81955984)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
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
In net/core/dev.c (ffffffff8193c582)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/rtnetlink.c (ffffffff8195b1fa)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffffffff819646dd)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff819779e4)
Location: include/linux/netdevice.h:3822
Inline: True
Inline callers:
  - net/core/net-sysfs.c:dormant_show
```
</details>
</li>
</ul>

## Differences
