# Function: <code>ext4_alloc_group_tables</code>

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
In fs/ext4/resize.c (ffffffff812c1c5e)
Location: fs/ext4/resize.c:244
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff812f175e)
Location: fs/ext4/resize.c:244
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff8130772e)
Location: fs/ext4/resize.c:244
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff81322245)
Location: fs/ext4/resize.c:245
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813469a1)
Location: fs/ext4/resize.c:246
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff8137476c)
Location: fs/ext4/resize.c:249
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff8138ccf6)
Location: fs/ext4/resize.c:251
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:251
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff813b4170-ffffffff813b45a6: ext4_alloc_group_tables (STB_LOCAL)
ffffffff813b792f-ffffffff813b7943: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813d032d)
Location: fs/ext4/resize.c:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8141a660-ffffffff8141ab1d: ext4_alloc_group_tables (STB_LOCAL)
ffffffff8141d0e4-ffffffff8141d0f8: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8142e1e0-ffffffff8142e69d: ext4_alloc_group_tables (STB_LOCAL)
ffffffff81bec5aa-ffffffff81bec5be: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81435280-ffffffff8143573d: ext4_alloc_group_tables (STB_LOCAL)
ffffffff81bde65c-ffffffff81bde670: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:283
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81488d30-ffffffff814891f3: ext4_alloc_group_tables (STB_LOCAL)
ffffffff81ccd177-ffffffff81ccd1b2: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:294
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8150b9c0-ffffffff8150bee0: ext4_alloc_group_tables (STB_LOCAL)
ffffffff81e7fff1-ffffffff81e8002e: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:297
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff815a6680-ffffffff815a6bb4: ext4_alloc_group_tables (STB_LOCAL)
ffffffff8207049f-ffffffff820704c8: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:297
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff815dcef0-ffffffff815dd459: ext4_alloc_group_tables (STB_LOCAL)
ffffffff820f0175-ffffffff820f019e: ext4_alloc_group_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:302
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81615920-ffffffff81615e89: ext4_alloc_group_tables (STB_LOCAL)
ffffffff821cd370-ffffffff821cd399: ext4_alloc_group_tables.cold (STB_LOCAL)
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
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a57f8)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffff8000104a57f8-ffff8000104a5bfc: ext4_alloc_group_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0667704)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
c0667704-c0667c78: ext4_alloc_group_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d2be0)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
c0000000005d2be0-c0000000005d307c: ext4_alloc_group_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_alloc_group_tables(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe0003266f6)
Location: fs/ext4/resize.c:278
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffe0003266f6-ffffffe000326a68: ext4_alloc_group_tables (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c890d)
Location: fs/ext4/resize.c:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b938d)
Location: fs/ext4/resize.c:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c5d9d)
Location: fs/ext4/resize.c:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813dafcd)
Location: fs/ext4/resize.c:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flexbg_size</code> ➡️ <code>unsigned int flexbg_size</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
