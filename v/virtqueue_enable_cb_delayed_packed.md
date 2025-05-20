# Function: <code>virtqueue_enable_cb_delayed_packed</code>

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
In drivers/virtio/virtio_ring.c (ffffffff81605263)
Location: drivers/virtio/virtio_ring.c:1465
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff816383f3)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff8165a1e3)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff81709f43)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff81727143)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff8170b132)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool virtqueue_enable_cb_delayed_packed(struct virtqueue *_vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1556
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
```
**Symbols:**

```
ffffffff817860d0-ffffffff817861ea: virtqueue_enable_cb_delayed_packed (STB_LOCAL)
ffffffff81cf43ad-ffffffff81cf4434: virtqueue_enable_cb_delayed_packed.cold (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffffffff818bda13)
Location: drivers/virtio/virtio_ring.c:1555
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff81a0cd73)
Location: drivers/virtio/virtio_ring.c:1740
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff81a55a03)
Location: drivers/virtio/virtio_ring.c:1768
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff81aa6a73)
Location: drivers/virtio/virtio_ring.c:1806
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffff800010822410)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (c093fd7c)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (c0000000008cc978)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffe000518d8c)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff81620083)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff816146d3)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff8164e023)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
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
In drivers/virtio/virtio_ring.c (ffffffff816686b3)
Location: drivers/virtio/virtio_ring.c:1470
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
