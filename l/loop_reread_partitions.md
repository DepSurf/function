# Function: <code>loop_reread_partitions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156e060)
Location: drivers/block/loop.c:635
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8156e060-ffffffff8156e0a8: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c3950)
Location: drivers/block/loop.c:630
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
```
**Symbols:**

```
ffffffff815c3950-ffffffff815c3998: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f21a0)
Location: drivers/block/loop.c:618
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
```
**Symbols:**

```
ffffffff815f21a0-ffffffff815f21e8: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816063b0)
Location: drivers/block/loop.c:629
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
```
**Symbols:**

```
ffffffff816063b0-ffffffff816063f8: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166e7d0)
Location: drivers/block/loop.c:612
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
```
**Symbols:**

```
ffffffff8166e7d0-ffffffff8166e818: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:638
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
```
**Symbols:**

```
ffffffff816aa2b0-ffffffff816aa2de: loop_reread_partitions (STB_LOCAL)
ffffffff816ad779-ffffffff816ad79a: loop_reread_partitions.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:637
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff816caea0-ffffffff816caec0: loop_reread_partitions (STB_LOCAL)
ffffffff816ce5f7-ffffffff816ce618: loop_reread_partitions.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:637
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81706470-ffffffff81706490: loop_reread_partitions (STB_LOCAL)
ffffffff81709d18-ffffffff81709d39: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8172a6c0-ffffffff8172a6e0: loop_reread_partitions (STB_LOCAL)
ffffffff8172e015-ffffffff8172e036: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817ea25d)
Location: drivers/block/loop.c:660
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fecba)
Location: drivers/block/loop.c:658
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e3954)
Location: drivers/block/loop.c:691
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:685
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff8186c3b0-ffffffff8186c3fe: loop_reread_partitions (STB_LOCAL)
ffffffff81d0574b-ffffffff81d0576c: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:513
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff819b4fa0-ffffffff819b4fff: loop_reread_partitions (STB_LOCAL)
ffffffff81ece119-ffffffff81ece13a: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b29dd0)
Location: drivers/block/loop.c:513
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81b29dd0-ffffffff81b29e63: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7a000)
Location: drivers/block/loop.c:513
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81b7a000-ffffffff81b7a093: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bcdf60)
Location: drivers/block/loop.c:509
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81bcdf60-ffffffff81bcdff3: loop_reread_partitions (STB_LOCAL)
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
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff8000109212a8)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff8000109212a8-ffff800010921300: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a05ffc)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0a05ffc-c0a06054: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c5560)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0000000009c5560-c0000000009c55d4: loop_reread_partitions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe00059fac8)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe00059fac8-ffffffe00059fb1e: loop_reread_partitions (STB_LOCAL)
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
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff816f04a0-ffffffff816f04c0: loop_reread_partitions (STB_LOCAL)
ffffffff816f3df5-ffffffff816f3e16: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff816ca5b0-ffffffff816ca5d0: loop_reread_partitions (STB_LOCAL)
ffffffff816cdef5-ffffffff816cdf16: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8171db80-ffffffff8171dba0: loop_reread_partitions (STB_LOCAL)
ffffffff817214d5-ffffffff817214f6: loop_reread_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void loop_reread_partitions(struct loop_device *lo, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:647
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81738f10-ffffffff81738f30: loop_reread_partitions (STB_LOCAL)
ffffffff8173c8a2-ffffffff8173c8c3: loop_reread_partitions.cold (STB_LOCAL)
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
