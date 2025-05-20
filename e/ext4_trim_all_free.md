# Function: <code>ext4_trim_all_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d5786)
Location: fs/ext4/mballoc.c:5095
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81305436)
Location: fs/ext4/mballoc.c:5098
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8131b406)
Location: fs/ext4/mballoc.c:5105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813127f6)
Location: fs/ext4/mballoc.c:5171
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81337072)
Location: fs/ext4/mballoc.c:5175
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8136566f)
Location: fs/ext4/mballoc.c:5145
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137da2f)
Location: fs/ext4/mballoc.c:5152
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a4240)
Location: fs/ext4/mballoc.c:5154
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff813a4240-ffffffff813a4821: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bd0b0)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff813bd0b0-ffffffff813bd691: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81409190)
Location: fs/ext4/mballoc.c:5420
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff81409190-ffffffff81409653: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141b680)
Location: fs/ext4/mballoc.c:5707
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff8141b680-ffffffff8141bb36: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81421900)
Location: fs/ext4/mballoc.c:6240
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff81421900-ffffffff81421e64: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81474860)
Location: fs/ext4/mballoc.c:6362
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff81474860-ffffffff81474a27: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks, bool set_trimmed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f6880)
Location: fs/ext4/mballoc.c:6449
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff814f6880-ffffffff814f6a75: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks, bool set_trimmed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81590d60)
Location: fs/ext4/mballoc.c:6418
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff81590d60-ffffffff81591032: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks, bool set_trimmed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c7db0)
Location: fs/ext4/mballoc.c:6994
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff815c7db0-ffffffff815c7fa5: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815ffa10)
Location: fs/ext4/mballoc.c:6841
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff815ffa10-ffffffff815ffbf5: ext4_trim_all_free (STB_LOCAL)
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
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010493e28)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffff800010493e28-ffff800010494348: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06553b4)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
c06553b4-c0655bc8: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005bcd50)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
c0000000005bcd50-c0000000005bd560: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe0003188e0)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffe0003188e0-ffffffe000318f42: ext4_trim_all_free (STB_LOCAL)
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
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b5690)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff813b5690-ffffffff813b5c71: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a6120)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff813a6120-ffffffff813a6701: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b2ef0)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff813b2ef0-ffffffff813b34d1: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c7a40)
Location: fs/ext4/mballoc.c:5175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff813c7a40-ffffffff813c8057: ext4_trim_all_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool set_trimmed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool set_trimmed</code>
</li>
</ul>
</details>
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
