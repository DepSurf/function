# Function: <code>napi_disable_pending</code>

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
In drivers/net/virtio_net.c (ffffffff815f0e05)
Location: include/linux/netdevice.h:395
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
```
```
In drivers/net/xen-netfront.c (ffffffff815fbe7c)
Location: include/linux/netdevice.h:395
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81718e9c)
Location: include/linux/netdevice.h:395
Inline: True
Inline callers:
  - net/core/dev.c:napi_watchdog
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
In drivers/net/virtio_net.c (ffffffff8165081d)
Location: include/linux/netdevice.h:400
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:skb_recv_done
```
```
In drivers/net/xen-netfront.c (ffffffff8165d287)
Location: include/linux/netdevice.h:400
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81783976)
Location: include/linux/netdevice.h:400
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
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
In net/core/dev.c (ffffffff817b0f2b)
Location: include/linux/netdevice.h:413
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
In net/core/dev.c (ffffffff817d1286)
Location: include/linux/netdevice.h:414
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
In net/core/dev.c (ffffffff8184b395)
Location: include/linux/netdevice.h:414
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
In net/core/dev.c (ffffffff8189578c)
Location: include/linux/netdevice.h:416
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
In net/core/dev.c (ffffffff818b73f8)
Location: include/linux/netdevice.h:427
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
In net/core/dev.c (ffffffff81903221)
Location: include/linux/netdevice.h:424
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
In net/core/dev.c (ffffffff81935fc1)
Location: include/linux/netdevice.h:428
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
In net/core/dev.c (ffffffff81a0ab72)
Location: include/linux/netdevice.h:433
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff81a0bd77)
Location: include/linux/netdevice.h:437
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff819f2d67)
Location: include/linux/netdevice.h:441
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff81aa3bd7)
Location: include/linux/netdevice.h:434
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff81c1c5c9)
Location: include/linux/netdevice.h:446
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff81dcd5e1)
Location: include/linux/netdevice.h:460
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff81e3e146)
Location: include/linux/netdevice.h:469
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff81efc9e6)
Location: include/linux/netdevice.h:474
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffff800010bd4578)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (c0cefd5c)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (c000000000cb3630)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffe00075e3d4)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
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
In net/core/dev.c (ffffffff818d5f91)
Location: include/linux/netdevice.h:428
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
In net/core/dev.c (ffffffff8188fdc9)
Location: include/linux/netdevice.h:428
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
In net/core/dev.c (ffffffff81926fc1)
Location: include/linux/netdevice.h:428
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
In net/core/dev.c (ffffffff8194861b)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
</details>
</li>
</ul>

## Differences
