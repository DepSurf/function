# Function: <code>virtqueue_add_sgs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bf7e0)
Location: drivers/virtio/virtio_ring.c:279
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:__virtblk_add_req
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff814bf7e0-ffffffff814bfb7f: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150fe20)
Location: drivers/virtio/virtio_ring.c:449
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:__virtblk_add_req
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff8150fe20-ffffffff815102c0: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153bf80)
Location: drivers/virtio/virtio_ring.c:449
Inline: False
```
**Symbols:**

```
ffffffff8153bf80-ffffffff8153c420: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f910)
Location: drivers/virtio/virtio_ring.c:453
Inline: False
```
**Symbols:**

```
ffffffff8154f910-ffffffff8154fd69: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b30d0)
Location: drivers/virtio/virtio_ring.c:452
Inline: False
```
**Symbols:**

```
ffffffff815b30d0-ffffffff815b355a: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb550)
Location: drivers/virtio/virtio_ring.c:451
Inline: False
```
**Symbols:**

```
ffffffff815eb550-ffffffff815eb9c2: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81606de0)
Location: drivers/virtio/virtio_ring.c:1720
Inline: False
```
**Symbols:**

```
ffffffff81606de0-ffffffff81606e6d: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81639240)
Location: drivers/virtio/virtio_ring.c:1725
Inline: False
```
**Symbols:**

```
ffffffff81639240-ffffffff81639305: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165afc0)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffff8165afc0-ffffffff8165b085: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170bc80)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffff8170bc80-ffffffff8170bd45: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81728af0)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81728af0-ffffffff81728bb5: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c210)
Location: drivers/virtio/virtio_ring.c:1726
Inline: False
```
**Symbols:**

```
ffffffff8170c210-ffffffff8170c2d5: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff81cf4ccf-ffffffff81cf4ce3: virtqueue_add_sgs.cold (STB_LOCAL)
ffffffff81788570-ffffffff81788641: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1828
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff81ebce40-ffffffff81ebce55: virtqueue_add_sgs.cold (STB_LOCAL)
ffffffff818bfb80-ffffffff818bfc6f: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2114
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff820943c6-ffffffff820943db: virtqueue_add_sgs.cold (STB_LOCAL)
ffffffff81a0fa10-ffffffff81a0faff: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2151
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/block/virtio_blk.c:virtblk_add_req
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff82115126-ffffffff8211513b: virtqueue_add_sgs.cold (STB_LOCAL)
ffffffff81a58ab0-ffffffff81a58b9f: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2228
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/block/virtio_blk.c:virtblk_add_req
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff821f2d68-ffffffff821f2d7d: virtqueue_add_sgs.cold (STB_LOCAL)
ffffffff81aa9e90-ffffffff81aa9f7f: virtqueue_add_sgs (STB_GLOBAL)
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
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010823ed0)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffff800010823ed0-ffff800010823fb8: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0941d44)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
c0941d44-c0941e10: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cdd10)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
c0000000008cdd10-c0000000008cde48: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051bff0)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffe00051bff0-ffffffe00051c09e: virtqueue_add_sgs (STB_GLOBAL)
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
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81620e60)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81620e60-ffffffff81620f25: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816154b0)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffff816154b0-ffffffff81615575: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164ee00)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
```
**Symbols:**

```
ffffffff8164ee00-ffffffff8164eec5: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int virtqueue_add_sgs(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81669490)
Location: drivers/virtio/virtio_ring.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81669490-ffffffff81669555: virtqueue_add_sgs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
