# Function: <code>blk_mq_pci_map_queues</code>

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
int blk_mq_pci_map_queues(struct blk_mq_tag_set *set, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81448ac0)
Location: block/blk-mq-pci.c:31
Inline: False
```
**Symbols:**

```
ffffffff81448ac0-ffffffff81448b53: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_tag_set *set, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81456f50)
Location: block/blk-mq-pci.c:31
Inline: True
```
**Symbols:**

```
ffffffff81456f50-ffffffff81457023: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_tag_set *set, struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81482ba0)
Location: block/blk-mq-pci.c:31
Inline: True
```
**Symbols:**

```
ffffffff81482ba0-ffffffff81482c5b: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_tag_set *set, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff814b7820)
Location: block/blk-mq-pci.c:32
Inline: True
```
**Symbols:**

```
ffffffff814b7820-ffffffff814b78d7: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff814cb3b0)
Location: block/blk-mq-pci.c:34
Inline: True
```
**Symbols:**

```
ffffffff814cb3b0-ffffffff814cb46c: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff814f9d30)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
ffffffff814f9d30-ffffffff814f9dec: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81517c00)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
ffffffff81517c00-ffffffff81517cbc: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81578460)
Location: block/blk-mq-pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81578460-ffffffff81578522: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81594e50)
Location: block/blk-mq-pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81594e50-ffffffff81594f12: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff8159bc10)
Location: block/blk-mq-pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff8159bc10-ffffffff8159bcd2: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81603fb0)
Location: block/blk-mq-pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81603fb0-ffffffff81604072: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff816b7630)
Location: block/blk-mq-pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff816b7630-ffffffff816b7716: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81777710)
Location: block/blk-mq-pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81777710-ffffffff81777803: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff817b7390)
Location: block/blk-mq-pci.c:25
Inline: False
```
**Symbols:**

```
ffffffff817b7390-ffffffff817b7483: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff817fbda0)
Location: block/blk-mq-pci.c:25
Inline: False
```
**Symbols:**

```
ffffffff817fbda0-ffffffff817fbe93: blk_mq_pci_map_queues (STB_GLOBAL)
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
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffff80001061f188)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
ffff80001061f188-ffff80001061f288: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (c07c6bdc)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
c07c6bdc-c07c6ce4: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (c0000000007be6e0)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
c0000000007be6e0-c0000000007be888: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffe000451d90)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
ffffffe000451d90-ffffffe000451e68: blk_mq_pci_map_queues (STB_GLOBAL)
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
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff815101e0)
Location: block/blk-mq-pci.c:26
Inline: True
Direct callers:
  - drivers/nvme/host/pci.c:nvme_pci_map_queues
```
**Symbols:**

```
ffffffff815101e0-ffffffff8151029c: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81500500)
Location: block/blk-mq-pci.c:26
Inline: True
Direct callers:
  - drivers/nvme/host/pci.c:nvme_pci_map_queues
```
**Symbols:**

```
ffffffff81500500-ffffffff815005bc: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff8150c270)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
ffffffff8150c270-ffffffff8150c32c: blk_mq_pci_map_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_pci_map_queues(struct blk_mq_queue_map *qmap, struct pci_dev *pdev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-pci.c (ffffffff81525950)
Location: block/blk-mq-pci.c:26
Inline: True
```
**Symbols:**

```
ffffffff81525950-ffffffff81525a0c: blk_mq_pci_map_queues (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int offset</code>
</li>
</ul>
</details>
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
