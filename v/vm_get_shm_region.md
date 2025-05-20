# Function: <code>vm_get_shm_region</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff817291d0)
Location: drivers/virtio/virtio_mmio.c:501
Inline: False
```
**Symbols:**

```
ffffffff817291d0-ffffffff8172924a: vm_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8170d960)
Location: drivers/virtio/virtio_mmio.c:501
Inline: False
```
**Symbols:**

```
ffffffff8170d960-ffffffff8170d9e0: vm_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8178a1c0)
Location: drivers/virtio/virtio_mmio.c:501
Inline: False
```
**Symbols:**

```
ffffffff8178a1c0-ffffffff8178a240: vm_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff818c18e0)
Location: drivers/virtio/virtio_mmio.c:514
Inline: False
```
**Symbols:**

```
ffffffff818c18e0-ffffffff818c1969: vm_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81a11810)
Location: drivers/virtio/virtio_mmio.c:519
Inline: False
```
**Symbols:**

```
ffffffff81a11810-ffffffff81a11899: vm_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81a5a7e0)
Location: drivers/virtio/virtio_mmio.c:536
Inline: False
```
**Symbols:**

```
ffffffff81a5a7e0-ffffffff81a5a869: vm_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vm_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81aabc20)
Location: drivers/virtio/virtio_mmio.c:536
Inline: False
```
**Symbols:**

```
ffffffff81aabc20-ffffffff81aabca9: vm_get_shm_region (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
