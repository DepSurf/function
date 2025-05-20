# Function: <code>blk_mq_update_nr_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81409610)
Location: block/blk-mq.c:2406
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81409610-ffffffff81409737: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81424010)
Location: block/blk-mq.c:2461
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81424010-ffffffff81424137: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432ff0)
Location: block/blk-mq.c:2646
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81432ff0-ffffffff81433121: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ebb0)
Location: block/blk-mq.c:2812
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff8145ebb0-ffffffff8145ecd2: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81492500)
Location: block/blk-mq.c:2876
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81492500-ffffffff81492623: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3269
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff814ac9e2-ffffffff814aca06: blk_mq_update_nr_hw_queues.cold.80 (STB_LOCAL)
ffffffff814ac080-ffffffff814ac3e8: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3304
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff814dacf0-ffffffff814dad17: blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
ffffffff814da2c0-ffffffff814da600: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3324
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff814f407d-ffffffff814f40a4: blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
ffffffff814f3680-ffffffff814f39c0: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81553f70)
Location: block/blk-mq.c:3547
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81553f70-ffffffff81553fac: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81570630)
Location: block/blk-mq.c:3677
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81570630-ffffffff8157066f: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81578590)
Location: block/blk-mq.c:3739
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81578590-ffffffff815785cf: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dd670)
Location: block/blk-mq.c:3796
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff815dd670-ffffffff815dd6af: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168b250)
Location: block/blk-mq.c:4560
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff8168b250-ffffffff8168b292: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81749240)
Location: block/blk-mq.c:4769
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81749240-ffffffff81749282: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81785980)
Location: block/blk-mq.c:4772
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81785980-ffffffff817859c2: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c8000)
Location: block/blk-mq.c:4802
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff817c8000-ffffffff817c8042: blk_mq_update_nr_hw_queues (STB_GLOBAL)
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
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2ec8)
Location: block/blk-mq.c:3324
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffff8000105f2ec8-ffff8000105f3214: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079efbc)
Location: block/blk-mq.c:3324
Inline: False
```
**Symbols:**

```
c079efbc-c079f324: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078a550)
Location: block/blk-mq.c:3324
Inline: False
```
**Symbols:**

```
c00000000078a550-c00000000078a9a8: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe0004316b4)
Location: block/blk-mq.c:3324
Inline: False
```
**Symbols:**

```
ffffffe0004316b4-ffffffe000431982: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3324
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_restore
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff814ec65d-ffffffff814ec684: blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
ffffffff814ebc60-ffffffff814ebfa0: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3324
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff814dcbad-ffffffff814dcbd4: blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
ffffffff814dc1b0-ffffffff814dc4f0: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3324
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff814e86ed-ffffffff814e8714: blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
ffffffff814e7cf0-ffffffff814e8030: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3324
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff8150168d-ffffffff815016b4: blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
ffffffff81500c90-ffffffff81500fd0: blk_mq_update_nr_hw_queues (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
