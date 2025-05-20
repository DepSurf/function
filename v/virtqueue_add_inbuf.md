# Function: <code>virtqueue_add_inbuf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bfdb0)
Location: drivers/virtio/virtio_ring.c:333
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff814bfdb0-ffffffff814c0036: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815102c0)
Location: drivers/virtio/virtio_ring.c:503
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff815102c0-ffffffff815105d8: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153c420)
Location: drivers/virtio/virtio_ring.c:503
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8153c420-ffffffff8153c738: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154fd70)
Location: drivers/virtio/virtio_ring.c:508
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8154fd70-ffffffff8155009f: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b3560)
Location: drivers/virtio/virtio_ring.c:507
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff815b3560-ffffffff815b38a0: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb9d0)
Location: drivers/virtio/virtio_ring.c:506
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff815eb9d0-ffffffff815ebcdb: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81606ea0)
Location: drivers/virtio/virtio_ring.c:1776
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81606ea0-ffffffff81606ecb: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81639ad0)
Location: drivers/virtio/virtio_ring.c:1781
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81639ad0-ffffffff8163a15c: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165bac0)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8165bac0-ffffffff8165c3bc: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170bda0)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff8170bda0-ffffffff8170bdec: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81728c10)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff81728c10-ffffffff81728c5c: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c330)
Location: drivers/virtio/virtio_ring.c:1782
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff8170c330-ffffffff8170c37c: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1880
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
```
**Symbols:**

```
ffffffff81cf4d0d-ffffffff81cf4d37: virtqueue_add_inbuf.cold (STB_LOCAL)
ffffffff817886d0-ffffffff81788742: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1884
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
```
**Symbols:**

```
ffffffff81ebce80-ffffffff81ebceab: virtqueue_add_inbuf.cold (STB_LOCAL)
ffffffff818bfd10-ffffffff818bfda9: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2170
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
```
**Symbols:**

```
ffffffff82094406-ffffffff82094431: virtqueue_add_inbuf.cold (STB_LOCAL)
ffffffff81a0fbc0-ffffffff81a0fc59: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2207
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/net/virtio_net.c:add_recvbuf_big
```
**Symbols:**

```
ffffffff82115199-ffffffff821151c4: virtqueue_add_inbuf.cold (STB_LOCAL)
ffffffff81a58d10-ffffffff81a58da9: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2284
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/net/virtio_net.c:add_recvbuf_big
```
**Symbols:**

```
ffffffff821f2d7d-ffffffff821f2da8: virtqueue_add_inbuf.cold (STB_LOCAL)
ffffffff81aa9f90-ffffffff81aaa029: virtqueue_add_inbuf (STB_GLOBAL)
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
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010824c08)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
```
**Symbols:**

```
ffff800010824c08-ffff800010825328: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0943358)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
c0943358-c0943e0c: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008ced10)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
c0000000008ced10-c0000000008cf964: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051b3dc)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffe00051b3dc-ffffffe00051bc08: virtqueue_add_inbuf (STB_GLOBAL)
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
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81621960)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81621960-ffffffff8162225c: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81615fb0)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81615fb0-ffffffff816168ac: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164f900)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/scsi/virtio_scsi.c:virtscsi_kick_event
```
**Symbols:**

```
ffffffff8164f900-ffffffff816501fc: virtqueue_add_inbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int virtqueue_add_inbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81669f90)
Location: drivers/virtio/virtio_ring.c:1780
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81669f90-ffffffff8166a88c: virtqueue_add_inbuf (STB_GLOBAL)
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
