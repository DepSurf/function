# Function: <code>vring_create_virtqueue_packed</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605fc0)
Location: drivers/virtio/virtio_ring.c:1549
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637910)
Location: drivers/virtio/virtio_ring.c:1554
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81637910-ffffffff81637c59: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659700)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81659700-ffffffff81659a49: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170be40)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8170be40-ffffffff8170c20a: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81728cb0)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81728cb0-ffffffff81729055: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c880)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8170c880-ffffffff8170cc33: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81788c70)
Location: drivers/virtio/virtio_ring.c:1658
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81788c70-ffffffff81788ff2: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bfe50)
Location: drivers/virtio/virtio_ring.c:1659
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff818bfe50-ffffffff818c0204: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1980
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81a0e860-ffffffff81a0eb1c: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
ffffffff82094104-ffffffff82094119: vring_create_virtqueue_packed.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2015
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81a578f0-ffffffff81a57bc9: vring_create_virtqueue_packed.isra.0 (STB_LOCAL)
ffffffff82114e56-ffffffff82114e6b: vring_create_virtqueue_packed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2053
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81aa8800-ffffffff81aa8b15: vring_create_virtqueue_packed.isra.0 (STB_LOCAL)
ffffffff821f2a9f-ffffffff821f2ab4: vring_create_virtqueue_packed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010823fb8)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffff800010823fb8-ffff800010824284: vring_create_virtqueue_packed.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (c094122c)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c094122c-c0941550: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cbaf0)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c0000000008cbaf0-c0000000008cbe7c: vring_create_virtqueue_packed.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519ed6)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffe000519ed6-ffffffe00051a14c: vring_create_virtqueue_packed.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f5a0)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8161f5a0-ffffffff8161f8e9: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613b40)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81613b40-ffffffff81613e8a: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d540)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8164d540-ffffffff8164d889: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81667bd0)
Location: drivers/virtio/virtio_ring.c:1553
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81667bd0-ffffffff81667f19: vring_create_virtqueue_packed.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
