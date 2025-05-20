# Function: <code>vring_alloc_desc_extra</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81787b60)
Location: drivers/virtio/virtio_ring.c:1639
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
**Symbols:**

```
ffffffff81787b60-ffffffff81787bbf: vring_alloc_desc_extra.constprop.0 (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffffffff818bed80)
Location: drivers/virtio/virtio_ring.c:1640
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
**Symbols:**

```
ffffffff818bed80-ffffffff818bedeb: vring_alloc_desc_extra.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vring_desc_extra *vring_alloc_desc_extra(unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0e370)
Location: drivers/virtio/virtio_ring.c:1825
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_state_extra_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_state_extra_split
```
**Symbols:**

```
ffffffff81a0e370-ffffffff81a0e3db: vring_alloc_desc_extra (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vring_desc_extra *vring_alloc_desc_extra(unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a572c0)
Location: drivers/virtio/virtio_ring.c:1853
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_state_extra_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_state_extra_split
```
**Symbols:**

```
ffffffff81a572c0-ffffffff81a5732b: vring_alloc_desc_extra (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vring_desc_extra *vring_alloc_desc_extra(unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa86f0)
Location: drivers/virtio/virtio_ring.c:1891
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_state_extra_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_state_extra_split
```
**Symbols:**

```
ffffffff81aa86f0-ffffffff81aa875b: vring_alloc_desc_extra (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
