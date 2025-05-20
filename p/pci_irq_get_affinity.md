# Function: <code>pci_irq_get_affinity</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c2130)
Location: drivers/pci/msi.c:1299
Inline: True
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
```
**Symbols:**

```
ffffffff814c2130-ffffffff814c2207: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc680)
Location: drivers/pci/msi.c:1243
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff814cc680-ffffffff814cc703: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150cbb0)
Location: drivers/pci/msi.c:1243
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff8150cbb0-ffffffff8150cc33: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81541a20)
Location: drivers/pci/msi.c:1242
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff81541a20-ffffffff81541aa3: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81558ce0)
Location: drivers/pci/msi.c:1262
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff81558ce0-ffffffff81558d6a: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81588d90)
Location: drivers/pci/msi.c:1291
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff81588d90-ffffffff81588e23: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aa730)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff815aa730-ffffffff815aa7c3: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816531c0)
Location: drivers/pci/msi.c:1292
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff816531c0-ffffffff81653253: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165cef0)
Location: drivers/pci/msi.c:1312
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff8165cef0-ffffffff8165cf83: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8163f490)
Location: drivers/pci/msi.c:1318
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff8163f490-ffffffff8163f523: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0760)
Location: drivers/pci/msi.c:1238
Inline: True
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff816b0760-ffffffff816b07ec: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d3d80)
Location: drivers/pci/msi/msi.c:1094
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff817d3d80-ffffffff817d3e21: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f4780)
Location: drivers/pci/msi/api.c:342
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff818f4780-ffffffff818f4823: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81937bb0)
Location: drivers/pci/msi/api.c:342
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff81937bb0-ffffffff81937c53: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980a10)
Location: drivers/pci/msi/api.c:342
Inline: False
Direct callers:
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff81980a10-ffffffff81980ab3: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713cb8)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffff800010713cb8-ffff800010713d88: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e894)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
c089e894-c089e9b0: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c0000000008835d0)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
c0000000008835d0-c0000000008836ac: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd7e4)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffe0004dd7e4-ffffffe0004dd878: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159df00)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff8159df00-ffffffff8159df93: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158d090)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff8158d090-ffffffff8158d123: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e480)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff8159e480-ffffffff8159e513: pci_irq_get_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *pci_irq_get_affinity(struct pci_dev *dev, int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b88b0)
Location: drivers/pci/msi.c:1292
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
```
**Symbols:**

```
ffffffff815b88b0-ffffffff815b8943: pci_irq_get_affinity (STB_GLOBAL)
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
