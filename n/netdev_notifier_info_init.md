# Function: <code>netdev_notifier_info_init</code>

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
In net/core/dev.c (ffffffff817147b0)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
```
```
In net/ipv6/addrconf.c (ffffffff817d1f39)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/core/dev.c (ffffffff8177c740)
Location: include/linux/netdevice.h:2326
Inline: True
Inline callers:
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
```
In net/ipv6/addrconf.c (ffffffff8183f909)
Location: include/linux/netdevice.h:2326
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/core/dev.c (ffffffff817a9eb0)
Location: include/linux/netdevice.h:2323
Inline: True
Inline callers:
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
```
In net/ipv6/addrconf.c (ffffffff81871539)
Location: include/linux/netdevice.h:2323
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/core/dev.c (ffffffff817c8500)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
```
In net/ipv6/addrconf.c (ffffffff81896299)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff81917659)
Location: include/linux/netdevice.h:2356
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff8196ed99)
Location: include/linux/netdevice.h:2441
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff819a4949)
Location: include/linux/netdevice.h:2529
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff81a10ca9)
Location: include/linux/netdevice.h:2520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff81a479e9)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3e479)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4d009)
Location: include/linux/netdevice.h:2777
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3ae09)
Location: include/linux/netdevice.h:2842
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81c015f9)
Location: include/linux/netdevice.h:2863
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d9b2b9)
Location: include/linux/netdevice.h:2895
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f69ed9)
Location: include/linux/netdevice.h:2920
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc9f19)
Location: include/linux/netdevice.h:2974
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820976a9)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffff800010d0a4bc)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (c0e10c3c)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (c000000000e3514c)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffe00085200e)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff819e7079)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff819a3e39)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff81a51af9)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
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
In net/ipv6/addrconf.c (ffffffff81a5da59)
Location: include/linux/netdevice.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
</details>
</li>
</ul>

## Differences
