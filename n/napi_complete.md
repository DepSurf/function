# Function: <code>napi_complete</code>

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
In drivers/net/xen-netfront.c (ffffffff815fbe5f)
Location: include/linux/netdevice.h:459
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/dev.c (ffffffff8171b159)
Location: include/linux/netdevice.h:459
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In drivers/net/xen-netfront.c (ffffffff8165bdc9)
Location: include/linux/netdevice.h:464
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/dev.c (ffffffff817839d8)
Location: include/linux/netdevice.h:464
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In drivers/net/xen-netfront.c (ffffffff81689bf9)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/dev.c (ffffffff817b0f93)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff817d12f6)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff8184b411)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff818957fa)
Location: include/linux/netdevice.h:467
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff818b7467)
Location: include/linux/netdevice.h:478
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff81903295)
Location: include/linux/netdevice.h:475
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff81936049)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff81a0abef)
Location: include/linux/netdevice.h:484
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
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
In net/core/dev.c (ffffffff81a0be31)
Location: include/linux/netdevice.h:493
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
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
In net/core/dev.c (ffffffff819f2e10)
Location: include/linux/netdevice.h:497
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
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
In net/core/dev.c (ffffffff81aa3c80)
Location: include/linux/netdevice.h:490
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
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
In net/core/dev.c (ffffffff81c1c665)
Location: include/linux/netdevice.h:502
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
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
In drivers/net/tun.c (ffffffff81bf26c4)
Location: include/linux/netdevice.h:516
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81dcd6b2)
Location: include/linux/netdevice.h:516
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
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
In drivers/net/tun.c (ffffffff81c4b382)
Location: include/linux/netdevice.h:528
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81e3e217)
Location: include/linux/netdevice.h:528
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
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
In drivers/net/tun.c (ffffffff81d00b2d)
Location: include/linux/netdevice.h:553
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81efcaba)
Location: include/linux/netdevice.h:553
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
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
In net/core/dev.c (ffff800010bd4644)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In drivers/net/ethernet/ti/cpsw.c (c0ad3be0)
Location: include/linux/netdevice.h:479
Inline: True
```
```
In net/core/dev.c (c0cefed8)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (c000000000cb36fc)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffe00075e49e)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff818d6019)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff8188fe4b)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff81927049)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In net/core/dev.c (ffffffff819486b4)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
</details>
</li>
</ul>

## Differences
