# Function: <code>dma_max_mapping_size</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81118020)
Location: kernel/dma/mapping.c:361
Inline: False
```
**Symbols:**

```
ffffffff81118020-ffffffff81118067: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811223b0)
Location: kernel/dma/mapping.c:395
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff811223b0-ffffffff811223f4: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112ea40)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8112ea40-ffffffff8112ea84: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d360)
Location: kernel/dma/mapping.c:386
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8113d360-ffffffff8113d3a4: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137bf0)
Location: kernel/dma/mapping.c:615
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81137bf0-ffffffff81137c34: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138c30)
Location: kernel/dma/mapping.c:705
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81138c30-ffffffff81138c74: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115bb40)
Location: kernel/dma/mapping.c:770
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8115bb40-ffffffff8115bb84: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811856b0)
Location: kernel/dma/mapping.c:762
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff811856b0-ffffffff81185706: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0f70)
Location: kernel/dma/mapping.c:798
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
**Symbols:**

```
ffffffff811c0f70-ffffffff811c0fc6: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d44d6)
Location: kernel/dma/mapping.c:802
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_opt_mapping_size
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
**Symbols:**

```
ffffffff811d3a60-ffffffff811d3ab6: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e9226)
Location: kernel/dma/mapping.c:818
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_opt_mapping_size
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/gpu/drm/drm_prime.c:drm_prime_pages_to_sg
```
**Symbols:**

```
ffffffff811e8700-ffffffff811e8756: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193ea8)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffff800010193ea8-ffff800010193efc: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e1214)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c03e1214-c03e1270: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f42d0)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c0000000001f42d0-c0000000001f435c: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000126200)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffe000126200-ffffffe000126244: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81127020)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff81127020-ffffffff81127064: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119a80)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff81119a80-ffffffff81119ac4: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124f10)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81124f10-ffffffff81124f54: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t dma_max_mapping_size(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131550)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81131550-ffffffff81131594: dma_max_mapping_size (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
