# Function: <code>dm_prepare_ioctl</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81806e30)
Location: drivers/md/dm.c:461
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81806e30-ffffffff81806f13: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81832e60)
Location: drivers/md/dm.c:512
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81832e60-ffffffff81832f43: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876da0)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81876da0-ffffffff81876eb8: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a8970)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff818a8970-ffffffff818a8a88: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81977b00)
Location: drivers/md/dm.c:523
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81977b00-ffffffff81977c18: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197c790)
Location: drivers/md/dm.c:520
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff8197c790-ffffffff8197c8a8: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960620)
Location: drivers/md/dm.c:525
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81960620-ffffffff81960738: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a082c0)
Location: drivers/md/dm.c:406
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81a082c0-ffffffff81a083d8: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b70660)
Location: drivers/md/dm.c:415
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81b70660-ffffffff81b7078e: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0d6d0)
Location: drivers/md/dm.c:410
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81d0d6d0-ffffffff81d0d7bb: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d765f0)
Location: drivers/md/dm.c:412
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81d765f0-ffffffff81d7671b: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2d820)
Location: drivers/md/dm.c:412
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81e2d820-ffffffff81e2d94b: dm_prepare_ioctl (STB_LOCAL)
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
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afcae8)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffff800010afcae8-ffff800010afcbf4: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdeb24)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
c0bdeb24-c0bdec68: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bed790)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
c000000000bed790-c000000000bed93c: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006eeeac)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffe0006eeeac-ffffffe0006eef82: dm_prepare_ioctl (STB_LOCAL)
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
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184e7f0)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff8184e7f0-ffffffff8184e908: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81815e10)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81815e10-ffffffff81815f28: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189de20)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff8189de20-ffffffff8189df38: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device *md, int *srcu_idx, struct block_device **bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818ba710)
Location: drivers/md/dm.c:492
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff818ba710-ffffffff818ba828: dm_prepare_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
