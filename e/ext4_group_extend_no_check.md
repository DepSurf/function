# Function: <code>ext4_group_extend_no_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812bf1a0)
Location: fs/ext4/resize.c:1640
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff812bf1a0-ffffffff812bf36b: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812eeac0)
Location: fs/ext4/resize.c:1640
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff812eeac0-ffffffff812eec78: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81304a90)
Location: fs/ext4/resize.c:1640
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff81304a90-ffffffff81304c48: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8131f620)
Location: fs/ext4/resize.c:1641
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff8131f620-ffffffff8131f7d8: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81343cc0)
Location: fs/ext4/resize.c:1669
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff81343cc0-ffffffff81343e78: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1672
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff81371ae0-ffffffff81371c7c: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813751c4-ffffffff813751f0: ext4_group_extend_no_check.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1672
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff81389fc0-ffffffff8138a15c: ext4_group_extend_no_check (STB_LOCAL)
ffffffff8138d5dc-ffffffff8138d608: ext4_group_extend_no_check.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1680
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff813b4a50-ffffffff813b4bea: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813b7943-ffffffff813b796d: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff813cd950-ffffffff813cdaea: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813d0c8e-ffffffff813d0cb8: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1694
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff81419e90-ffffffff8141a032: ext4_group_extend_no_check (STB_LOCAL)
ffffffff8141d0ba-ffffffff8141d0e4: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1702
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff8142db30-ffffffff8142dd4d: ext4_group_extend_no_check (STB_LOCAL)
ffffffff81bec56c-ffffffff81bec5aa: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1702
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff814347f0-ffffffff81434a0a: ext4_group_extend_no_check (STB_LOCAL)
ffffffff81bde61e-ffffffff81bde65c: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1713
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff81488250-ffffffff81488473: ext4_group_extend_no_check (STB_LOCAL)
ffffffff81ccd0b5-ffffffff81ccd0f3: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1736
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff8150d790-ffffffff8150d9a8: ext4_group_extend_no_check (STB_LOCAL)
ffffffff81e802cf-ffffffff81e80304: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815a8580)
Location: fs/ext4/resize.c:1771
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff815a8580-ffffffff815a87c7: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815dee00)
Location: fs/ext4/resize.c:1770
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff815dee00-ffffffff815df047: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff816178e0)
Location: fs/ext4/resize.c:1769
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff816178e0-ffffffff81617b27: ext4_group_extend_no_check (STB_LOCAL)
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
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a6ef8)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffff8000104a6ef8-ffff8000104a70e4: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0668d00)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
c0668d00-c0668ec8: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d36f0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
c0000000005d36f0-c0000000005d3988: ext4_group_extend_no_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000326ea0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffe000326ea0-ffffffe000327030: ext4_group_extend_no_check (STB_LOCAL)
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
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff813c5f30-ffffffff813c60ca: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813c926e-ffffffff813c9298: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff813b69b0-ffffffff813b6b4a: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813b9cee-ffffffff813b9d18: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff813c33c0-ffffffff813c355a: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813c66fe-ffffffff813c6728: ext4_group_extend_no_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_group_extend_no_check(struct super_block *sb, ext4_fsblk_t o_blocks_count, ext4_grpblk_t add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1716
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
**Symbols:**

```
ffffffff813d8570-ffffffff813d870a: ext4_group_extend_no_check (STB_LOCAL)
ffffffff813db92e-ffffffff813db958: ext4_group_extend_no_check.cold (STB_LOCAL)
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
