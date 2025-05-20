# Function: <code>netdev_queue_numa_node_write</code>

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
In net/core/dev.c (ffffffff817159ab)
Location: include/linux/netdevice.h:604
Inline: True
Inline callers:
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
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
In net/core/dev.c (ffffffff817844f0)
Location: include/linux/netdevice.h:606
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
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
In net/core/dev.c (ffffffff817b1af4)
Location: include/linux/netdevice.h:596
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
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
In net/core/dev.c (ffffffff817cb84e)
Location: include/linux/netdevice.h:596
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
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
In net/core/dev.c (ffffffff8184509d)
Location: include/linux/netdevice.h:596
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
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
In net/core/dev.c (ffffffff818912f0)
Location: include/linux/netdevice.h:607
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
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
In net/core/dev.c (ffffffff818b1920)
Location: include/linux/netdevice.h:650
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff818fe6c0)
Location: include/linux/netdevice.h:648
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff819309fd)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff81a0462f)
Location: include/linux/netdevice.h:657
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff81a0668f)
Location: include/linux/netdevice.h:657
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff819ed1e5)
Location: include/linux/netdevice.h:650
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff81a9e401)
Location: include/linux/netdevice.h:643
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff81c12c38)
Location: include/linux/netdevice.h:671
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff81dc2d5c)
Location: include/linux/netdevice.h:685
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff81e32201)
Location: include/linux/netdevice.h:697
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffffffff81ef06b1)
Location: include/linux/netdevice.h:726
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
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
In net/core/dev.c (ffff800010bcc8a4)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:652
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
In net/core/dev.c (c000000000cabc1c)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:652
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
In net/core/dev.c (ffffffff818d09fd)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff8188a8dd)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff819219fd)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff819403cd)
Location: include/linux/netdevice.h:652
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:__netif_set_xps_queue
```
</details>
</li>
</ul>

## Differences
