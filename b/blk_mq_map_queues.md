# Function: <code>blk_mq_map_queues</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81427b80)
Location: block/blk-mq-cpumap.c:34
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81427b80-ffffffff81427d20: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81435030)
Location: block/blk-mq-cpumap.c:38
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81435030-ffffffff81435110: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81460c40)
Location: block/blk-mq-cpumap.c:38
Inline: False
Direct callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81460c40-ffffffff81460d0d: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81494520)
Location: block/blk-mq-cpumap.c:33
Inline: False
Direct callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81494520-ffffffff814945c4: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814ae650)
Location: block/blk-mq-cpumap.c:34
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff814ae650-ffffffff814ae6fc: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814dc8f0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff814dc8f0-ffffffff814dc9b3: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814f5d10)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff814f5d10-ffffffff814f5e28: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81556730)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81556730-ffffffff81556848: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81572f80)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81572f80-ffffffff81573098: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8157afa0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_queue_map
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff8157afa0-ffffffff8157b0d7: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff815e02c0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff815e02c0-ffffffff815e042b: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8168ecf0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff8168ecf0-ffffffff8168ee64: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8174d790)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff8174d790-ffffffff8174d901: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81789db0)
Location: block/blk-mq-cpumap.c:18
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - drivers/block/virtio_blk.c:virtblk_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81789db0-ffffffff81789e8a: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff817cc530)
Location: block/blk-mq-cpumap.c:18
Inline: False
Direct callers:
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - drivers/block/virtio_blk.c:virtblk_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
  - drivers/scsi/virtio_scsi.c:virtscsi_map_queues
```
**Symbols:**

```
ffffffff817cc530-ffffffff817cc60a: blk_mq_map_queues (STB_GLOBAL)
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
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffff8000105f6040)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffff8000105f6040-ffff8000105f61bc: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (c07a1934)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
c07a1934-c07a1af4: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (c00000000078e0b0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
c00000000078e0b0-c00000000078e2f0: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffe000433bc0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffe000433bc0-ffffffe000433d08: blk_mq_map_queues (STB_GLOBAL)
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
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814ee2f0)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
  - drivers/nvme/host/pci.c:nvme_pci_map_queues
```
**Symbols:**

```
ffffffff814ee2f0-ffffffff814ee408: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814de840)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
  - drivers/nvme/host/pci.c:nvme_pci_map_queues
```
**Symbols:**

```
ffffffff814de840-ffffffff814de958: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814ea380)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff814ea380-ffffffff814ea498: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_queue_map *qmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81503350)
Location: block/blk-mq-cpumap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - drivers/scsi/scsi_lib.c:scsi_map_queues
```
**Symbols:**

```
ffffffff81503350-ffffffff81503468: blk_mq_map_queues (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_queue_map *qmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_tag_set *set</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
