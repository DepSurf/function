# Function: <code>vp_get_shm_region</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:506
Inline: False
```
**Symbols:**

```
ffffffff8172a020-ffffffff8172a0f9: vp_get_shm_region (STB_LOCAL)
ffffffff81c047ef-ffffffff81c0480f: vp_get_shm_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:348
Inline: False
```
**Symbols:**

```
ffffffff8170e780-ffffffff8170e93c: vp_get_shm_region (STB_LOCAL)
ffffffff81bf64dc-ffffffff81bf651f: vp_get_shm_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:348
Inline: False
```
**Symbols:**

```
ffffffff8178b010-ffffffff8178b262: vp_get_shm_region (STB_LOCAL)
ffffffff81cf5008-ffffffff81cf504b: vp_get_shm_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:354
Inline: False
```
**Symbols:**

```
ffffffff818c2ba0-ffffffff818c2d15: vp_get_shm_region (STB_LOCAL)
ffffffff81ebd18a-ffffffff81ebd1ab: vp_get_shm_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a12e20)
Location: drivers/virtio/virtio_pci_modern.c:450
Inline: False
```
**Symbols:**

```
ffffffff81a12e20-ffffffff81a12fb0: vp_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a5be90)
Location: drivers/virtio/virtio_pci_modern.c:460
Inline: False
```
**Symbols:**

```
ffffffff81a5be90-ffffffff81a5c007: vp_get_shm_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vp_get_shm_region(struct virtio_device *vdev, struct virtio_shm_region *region, u8 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aad120)
Location: drivers/virtio/virtio_pci_modern.c:705
Inline: False
```
**Symbols:**

```
ffffffff81aad120-ffffffff81aad297: vp_get_shm_region (STB_LOCAL)
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
