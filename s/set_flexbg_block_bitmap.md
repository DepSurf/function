# Function: <code>set_flexbg_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t block, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812bf890)
Location: fs/ext4/resize.c:408
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812bf890-ffffffff812bfa13: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t block, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812eede0)
Location: fs/ext4/resize.c:408
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812eede0-ffffffff812eef63: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t block, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81304db0)
Location: fs/ext4/resize.c:408
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81304db0-ffffffff81304f33: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t block, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81320460)
Location: fs/ext4/resize.c:409
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81320460-ffffffff813205db: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81344b30)
Location: fs/ext4/resize.c:419
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81344b30-ffffffff81344ccd: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81371de0)
Location: fs/ext4/resize.c:422
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81371de0-ffffffff81371f7a: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8138a2c0)
Location: fs/ext4/resize.c:424
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8138a2c0-ffffffff8138a48c: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b5190)
Location: fs/ext4/resize.c:424
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813b5190-ffffffff813b534d: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813cdc50)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813cdc50-ffffffff813cde0d: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141a040)
Location: fs/ext4/resize.c:433
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff8141a040-ffffffff8141a24b: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142dd50)
Location: fs/ext4/resize.c:433
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff8142dd50-ffffffff8142df5b: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81434a10)
Location: fs/ext4/resize.c:433
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81434a10-ffffffff81434c18: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:439
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81488480-ffffffff814886a3: set_flexbg_block_bitmap (STB_LOCAL)
ffffffff81ccd0f3-ffffffff81ccd138: set_flexbg_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:450
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff8150bee0-ffffffff8150c165: set_flexbg_block_bitmap (STB_LOCAL)
ffffffff81e8002e-ffffffff81e80073: set_flexbg_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:453
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff815a6bd0-ffffffff815a6e55: set_flexbg_block_bitmap (STB_LOCAL)
ffffffff820704c8-ffffffff8207050d: set_flexbg_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:453
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff815dd470-ffffffff815dd6f5: set_flexbg_block_bitmap (STB_LOCAL)
ffffffff820f019e-ffffffff820f01e3: set_flexbg_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:458
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81615ea0-ffffffff81616134: set_flexbg_block_bitmap (STB_LOCAL)
ffffffff821cd399-ffffffff821cd3de: set_flexbg_block_bitmap.cold (STB_LOCAL)
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
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a5eb8)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffff8000104a5eb8-ffff8000104a6084: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0667edc)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
c0667edc-c06680d4: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d3ba0)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
c0000000005d3ba0-c0000000005d3e3c: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe0003271cc)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffe0003271cc-ffffffe000327368: set_flexbg_block_bitmap (STB_LOCAL)
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
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c6230)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813c6230-ffffffff813c63ed: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b6cb0)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813b6cb0-ffffffff813b6e6d: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c36c0)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813c36c0-ffffffff813c387d: set_flexbg_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_flexbg_block_bitmap(struct super_block *sb, handle_t *handle, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t first_cluster, ext4_fsblk_t last_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813d8870)
Location: fs/ext4/resize.c:451
Inline: False
Direct callers:
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813d8870-ffffffff813d8a2d: set_flexbg_block_bitmap (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>ext4_fsblk_t first_cluster</code>
</li>
<li>
<b>Param added. </b>
<code>ext4_fsblk_t last_cluster</code>
</li>
<li>
<b>Param removed. </b>
<code>ext4_fsblk_t block</code>
</li>
<li>
<b>Param removed. </b>
<code>ext4_group_t count</code>
</li>
</ul>
</details>
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
