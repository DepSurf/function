# Function: <code>dev_kfree_skb_irq</code>

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
In drivers/net/xen-netfront.c (ffffffff815fa9d5)
Location: include/linux/netdevice.h:3033
Inline: True
```
```
In net/core/netpoll.c (ffffffff817391f3)
Location: include/linux/netdevice.h:3033
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff8165a896)
Location: include/linux/netdevice.h:3256
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a54af)
Location: include/linux/netdevice.h:3256
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff816885f6)
Location: include/linux/netdevice.h:3195
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d3f1e)
Location: include/linux/netdevice.h:3195
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff8169d95d)
Location: include/linux/netdevice.h:3234
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f3298)
Location: include/linux/netdevice.h:3234
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff817089bd)
Location: include/linux/netdevice.h:3259
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e6a8)
Location: include/linux/netdevice.h:3259
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff8174771c)
Location: include/linux/netdevice.h:3361
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bf83c)
Location: include/linux/netdevice.h:3361
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff8176b816)
Location: include/linux/netdevice.h:3577
Inline: True
```
```
In net/core/netpoll.c (ffffffff818e8662)
Location: include/linux/netdevice.h:3577
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff817a961b)
Location: include/linux/netdevice.h:3594
Inline: True
```
```
In net/core/netpoll.c (ffffffff81937d72)
Location: include/linux/netdevice.h:3594
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff817cd08b)
Location: include/linux/netdevice.h:3608
Inline: True
```
```
In net/core/netpoll.c (ffffffff8196ac32)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff8189871c)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In net/core/dev.c (ffffffff81a050db)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81a3e92e)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff818a6b3c)
Location: include/linux/netdevice.h:3882
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In net/core/dev.c (ffffffff81a060eb)
Location: include/linux/netdevice.h:3882
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81a416ce)
Location: include/linux/netdevice.h:3882
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff8188a3a9)
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/dev.c (ffffffff819edffb)
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81a2676e)
Location: include/linux/netdevice.h:3967
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff8191cdf2)
Location: include/linux/netdevice.h:3981
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81a9f29b)
Location: include/linux/netdevice.h:3981
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81adb4e9)
Location: include/linux/netdevice.h:3981
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff81a72b53)
Location: include/linux/netdevice.h:3771
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81c0f514)
Location: include/linux/netdevice.h:3771
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81c5c585)
Location: include/linux/netdevice.h:3771
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff81c052d3)
Location: include/linux/netdevice.h:3816
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81dbf304)
Location: include/linux/netdevice.h:3816
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81e12c58)
Location: include/linux/netdevice.h:3816
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff81c6a9e3)
Location: include/linux/netdevice.h:3875
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81e2efb4)
Location: include/linux/netdevice.h:3875
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81e86578)
Location: include/linux/netdevice.h:3875
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffffffff81d1f3c3)
Location: include/linux/netdevice.h:3946
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81eedc34)
Location: include/linux/netdevice.h:3946
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
```
```
In net/core/netpoll.c (ffffffff81f48588)
Location: include/linux/netdevice.h:3946
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
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
In drivers/net/xen-netfront.c (ffff800010a06ca0)
Location: include/linux/netdevice.h:3608
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11238)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In net/core/netpoll.c (c0d290e8)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In net/core/netpoll.c (c000000000cfda74)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In net/core/netpoll.c (ffffffe00078d498)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff81791b9b)
Location: include/linux/netdevice.h:3608
Inline: True
```
```
In net/core/netpoll.c (ffffffff8190ac02)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In net/core/netpoll.c (ffffffff818c49a2)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff817c1f0b)
Location: include/linux/netdevice.h:3608
Inline: True
```
```
In net/core/netpoll.c (ffffffff8195bc32)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
In drivers/net/xen-netfront.c (ffffffff817dc1cb)
Location: include/linux/netdevice.h:3608
Inline: True
```
```
In net/core/netpoll.c (ffffffff8197e032)
Location: include/linux/netdevice.h:3608
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
</details>
</li>
</ul>

## Differences
