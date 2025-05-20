# Function: <code>ext4_group_add_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d51c0)
Location: fs/ext4/mballoc.c:4910
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff812d51c0-ffffffff812d565d: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81304e80)
Location: fs/ext4/mballoc.c:4913
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff81304e80-ffffffff8130530f: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8131ae50)
Location: fs/ext4/mballoc.c:4920
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff8131ae50-ffffffff8131b2df: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81312210)
Location: fs/ext4/mballoc.c:4986
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff81312210-ffffffff813126c2: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813369d0)
Location: fs/ext4/mballoc.c:4986
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813369d0-ffffffff81336e99: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81364fe0)
Location: fs/ext4/mballoc.c:4956
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff81364fe0-ffffffff81365497: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137d3a0)
Location: fs/ext4/mballoc.c:4963
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff8137d3a0-ffffffff8137d857: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a6f60)
Location: fs/ext4/mballoc.c:4965
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813a6f60-ffffffff813a7424: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bfdf0)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813bfdf0-ffffffff813c02b4: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8140bed0)
Location: fs/ext4/mballoc.c:5230
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff8140bed0-ffffffff8140c3e7: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141f300)
Location: fs/ext4/mballoc.c:5517
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff8141f300-ffffffff8141f831: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81425c40)
Location: fs/ext4/mballoc.c:6050
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff81425c40-ffffffff8142610b: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6126
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff81ccc5f5-ffffffff81ccc65a: ext4_group_add_blocks.cold (STB_LOCAL)
ffffffff81479810-ffffffff81479d08: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6217
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff81e7f4e4-ffffffff81e7f567: ext4_group_add_blocks.cold (STB_LOCAL)
ffffffff814fb9c0-ffffffff814fbeec: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6186
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff8206f9ce-ffffffff8206fa51: ext4_group_add_blocks.cold (STB_LOCAL)
ffffffff815961a0-ffffffff81596652: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6762
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff820ef5c2-ffffffff820ef645: ext4_group_add_blocks.cold (STB_LOCAL)
ffffffff815ccb70-ffffffff815cd094: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6643
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff821cc6d6-ffffffff821cc73e: ext4_group_add_blocks.cold (STB_LOCAL)
ffffffff81605640-ffffffff81605973: ext4_group_add_blocks (STB_GLOBAL)
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
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff8000104969e8)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffff8000104969e8-ffff800010496ec8: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06589e4)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
c06589e4-c0659000: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005c0be0)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
c0000000005c0be0-c0000000005c12d4: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe00031b4ac)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffe00031b4ac-ffffffe00031b938: ext4_group_add_blocks (STB_GLOBAL)
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
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b83d0)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813b83d0-ffffffff813b8894: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a8e60)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813a8e60-ffffffff813a9324: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b5c30)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813b5c30-ffffffff813b60f4: ext4_group_add_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_group_add_blocks(handle_t *handle, struct super_block *sb, ext4_fsblk_t block, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813ca920)
Location: fs/ext4/mballoc.c:4985
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend_no_check
```
**Symbols:**

```
ffffffff813ca920-ffffffff813cadfc: ext4_group_add_blocks (STB_GLOBAL)
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
