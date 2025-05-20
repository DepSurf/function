# Function: <code>netdev_phys_item_id_same</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8188a5b2)
Location: include/linux/netdevice.h:773
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_get_dev_by_nhs
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
In net/switchdev/switchdev.c (ffffffff818beae1)
Location: include/linux/netdevice.h:763
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
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
In net/switchdev/switchdev.c (ffffffff818e556a)
Location: include/linux/netdevice.h:763
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
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
In net/ipv4/ipmr.c (ffffffff818ea30c)
Location: include/linux/netdevice.h:762
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff8196b14a)
Location: include/linux/netdevice.h:762
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
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
In net/ipv4/ipmr.c (ffffffff819407eb)
Location: include/linux/netdevice.h:774
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff819c4cca)
Location: include/linux/netdevice.h:774
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
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
In net/ipv4/ipmr.c (ffffffff8197066e)
Location: include/linux/netdevice.h:825
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/switchdev/switchdev.c (ffffffff819fc34a)
Location: include/linux/netdevice.h:825
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
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
In net/core/dev.c (ffffffff818fa709)
Location: include/linux/netdevice.h:823
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff819d9f00)
Location: include/linux/netdevice.h:823
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff8192c849)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81a10df1)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff819ffe27)
Location: include/linux/netdevice.h:832
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81b02635)
Location: include/linux/netdevice.h:832
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff819ffb87)
Location: include/linux/netdevice.h:832
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81b109f5)
Location: include/linux/netdevice.h:832
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff819e6367)
Location: include/linux/netdevice.h:842
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81afe60d)
Location: include/linux/netdevice.h:842
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff81a96897)
Location: include/linux/netdevice.h:835
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81bbfe23)
Location: include/linux/netdevice.h:835
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff81c0d740)
Location: include/linux/netdevice.h:865
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81d547e3)
Location: include/linux/netdevice.h:865
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff81dbd380)
Location: include/linux/netdevice.h:879
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81f1e9f0)
Location: include/linux/netdevice.h:879
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff81e2dbb0)
Location: include/linux/netdevice.h:894
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81f7e4f0)
Location: include/linux/netdevice.h:894
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff81eebf00)
Location: include/linux/netdevice.h:897
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff82044bb0)
Location: include/linux/netdevice.h:897
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffff800010bc8e28)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffff800010cccb78)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (c0ce504c)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (c0dd7178)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (c000000000ca5868)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (c000000000de8af0)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffe000755558)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffe00081ec1a)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff818cc849)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff819b0781)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff818868d9)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff8196cdb1)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff8191d849)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81a1b021)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/dev.c (ffffffff8193ed59)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/core/dev.c:netdev_port_same_parent_id
```
```
In net/ipv4/ipmr.c (ffffffff81a25f01)
Location: include/linux/netdevice.h:827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
</ul>

## Differences
