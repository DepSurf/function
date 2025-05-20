# Function: <code>mb_find_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812cd180)
Location: fs/ext4/mballoc.c:1501
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_check_limits
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
**Symbols:**

```
ffffffff812cd180-ffffffff812cd344: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812fcab0)
Location: fs/ext4/mballoc.c:1510
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff812fcab0-ffffffff812fcc6b: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81312a50)
Location: fs/ext4/mballoc.c:1510
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81312a50-ffffffff81312c0b: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130a460)
Location: fs/ext4/mballoc.c:1508
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8130a460-ffffffff8130a65b: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8132ef40)
Location: fs/ext4/mballoc.c:1508
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8132ef40-ffffffff8132f13b: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8135d510)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8135d510-ffffffff8135d709: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81375a40)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81375a40-ffffffff81375c39: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8139f000-ffffffff8139f1b8: mb_find_extent (STB_LOCAL)
ffffffff813a78e5-ffffffff813a7942: mb_find_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b7e20)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813b7e20-ffffffff813b801f: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81403730)
Location: fs/ext4/mballoc.c:1555
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81403730-ffffffff81403927: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81416870)
Location: fs/ext4/mballoc.c:1525
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81416870-ffffffff81416a68: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141c8f0)
Location: fs/ext4/mballoc.c:1860
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8141c8f0-ffffffff8141caed: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1864
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81471320-ffffffff8147155a: mb_find_extent (STB_LOCAL)
ffffffff81ccb6f6-ffffffff81ccb7d5: mb_find_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1861
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff814f2a10-ffffffff814f2c85: mb_find_extent (STB_LOCAL)
ffffffff81e7e986-ffffffff81e7ea69: mb_find_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1818
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8158d310-ffffffff8158d585: mb_find_extent (STB_LOCAL)
ffffffff8206ef17-ffffffff8206effa: mb_find_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1958
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
**Symbols:**

```
ffffffff815c3dc0-ffffffff815c402f: mb_find_extent (STB_LOCAL)
ffffffff820eed72-ffffffff820eee3c: mb_find_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1979
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
**Symbols:**

```
ffffffff815fc0f0-ffffffff815fc32d: mb_find_extent (STB_LOCAL)
ffffffff821cbe34-ffffffff821cbefc: mb_find_extent.cold (STB_LOCAL)
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
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff80001048e0d0)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffff80001048e0d0-ffff80001048e300: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c064eee8)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
c064eee8-c064f154: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005b4e60)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
c0000000005b4e60-c0000000005b514c: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe0003134ca)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffe0003134ca-ffffffe000313686: mb_find_extent (STB_LOCAL)
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
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b0400)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813b0400-ffffffff813b05ff: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a0e90)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813a0e90-ffffffff813a108f: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813adc60)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813adc60-ffffffff813ade5f: mb_find_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mb_find_extent(struct ext4_buddy *e4b, int block, int needed, struct ext4_free_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c2620)
Location: fs/ext4/mballoc.c:1493
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813c2620-ffffffff813c281f: mb_find_extent (STB_LOCAL)
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
