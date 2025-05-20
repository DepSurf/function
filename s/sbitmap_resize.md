# Function: <code>sbitmap_resize</code>

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
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148204d)
Location: lib/sbitmap.c:65
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81481f90-ffffffff81481fe3: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b2b0)
Location: lib/sbitmap.c:67
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff8148b1d0-ffffffff8148b223: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c73d0)
Location: lib/sbitmap.c:67
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814c72f0-ffffffff814c7343: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f89bc)
Location: lib/sbitmap.c:67
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814f8160-ffffffff814f81ab: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150cc80)
Location: lib/sbitmap.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8150cc80-ffffffff8150cdab: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b390)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8153b390-ffffffff8153b498: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c170)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8155c170-ffffffff8155c278: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e55d0)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff815e55d0-ffffffff815e56d6: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8160a310)
Location: lib/sbitmap.c:79
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8160a310-ffffffff8160a3a2: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed810)
Location: lib/sbitmap.c:128
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff815ed810-ffffffff815ed8a5: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:128
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff81cdef99-ffffffff81cdefb7: sbitmap_resize.cold (STB_LOCAL)
ffffffff8165a750-ffffffff8165a7fc: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:123
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
  - drivers/scsi/scsi.c:scsi_track_queue_full
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81ea5304-ffffffff81ea5322: sbitmap_resize.cold (STB_LOCAL)
ffffffff81772c10-ffffffff81772c92: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:123
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
  - drivers/scsi/scsi.c:scsi_track_queue_full
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff8208d708-ffffffff8208d726: sbitmap_resize.cold (STB_LOCAL)
ffffffff818a3080-ffffffff818a3102: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:123
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
  - drivers/scsi/scsi.c:scsi_track_queue_full
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff8210da9c-ffffffff8210daba: sbitmap_resize.cold (STB_LOCAL)
ffffffff818e5560-ffffffff818e55e4: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:123
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
  - drivers/scsi/scsi.c:scsi_track_queue_full
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff821eb6d9-ffffffff821eb6f7: sbitmap_resize.cold (STB_LOCAL)
ffffffff8192c560-ffffffff8192c5e4: sbitmap_resize (STB_GLOBAL)
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
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff800010669d40)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffff800010669d40-ffff800010669df8: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c08122b8)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
c08122b8-c081241c: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081eec0)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
c00000000081eec0-c00000000081f07c: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe0004944da)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffe0004944da-ffffffe0004945e8: sbitmap_resize (STB_GLOBAL)
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
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554760)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff81554760-ffffffff81554868: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815449e0)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff815449e0-ffffffff81544ae8: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815504a0)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff815504a0-ffffffff815505a8: sbitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sbitmap_resize(struct sbitmap *sb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a2e0)
Location: lib/sbitmap.c:89
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8156a2e0-ffffffff8156a3e8: sbitmap_resize (STB_GLOBAL)
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
