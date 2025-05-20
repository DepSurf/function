# Function: <code>ext4_get_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812bed30)
Location: fs/ext4/resize.c:1192
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812bed30-ffffffff812bed81: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812ee660)
Location: fs/ext4/resize.c:1192
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812ee660-ffffffff812ee6b1: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81304630)
Location: fs/ext4/resize.c:1192
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81304630-ffffffff81304681: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8131f1c0)
Location: fs/ext4/resize.c:1193
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8131f1c0-ffffffff8131f211: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81343860)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81343860-ffffffff813438b1: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81371670)
Location: fs/ext4/resize.c:1222
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81371670-ffffffff813716c1: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81389b40)
Location: fs/ext4/resize.c:1222
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81389b40-ffffffff81389b91: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b45b0)
Location: fs/ext4/resize.c:1230
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813b45b0-ffffffff813b4604: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813cd4b0)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813cd4b0-ffffffff813cd504: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff814195c0)
Location: fs/ext4/resize.c:1240
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff814195c0-ffffffff81419616: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142cc90)
Location: fs/ext4/resize.c:1245
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8142cc90-ffffffff8142ccea: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff81433970)
Location: fs/ext4/resize.c:1245
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81433970-ffffffff814339cb: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff81487320)
Location: fs/ext4/resize.c:1255
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81487320-ffffffff8148737b: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff8150acb0)
Location: fs/ext4/resize.c:1277
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8150acb0-ffffffff8150ad14: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff815a5880)
Location: fs/ext4/resize.c:1293
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815a5880-ffffffff815a58e4: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff815dc100)
Location: fs/ext4/resize.c:1293
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815dc100-ffffffff815dc164: ext4_get_bitmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (ffffffff816148c0)
Location: fs/ext4/resize.c:1295
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff816148c0-ffffffff81614933: ext4_get_bitmap.isra.0 (STB_LOCAL)
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
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a5c00)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffff8000104a5c00-ffff8000104a5c6c: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0667c78)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c0667c78-c0667ce8: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d3080)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c0000000005d3080-c0000000005d3118: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000326a68)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffe000326a68-ffffffe000326aca: ext4_get_bitmap (STB_LOCAL)
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
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c5a90)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813c5a90-ffffffff813c5ae4: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b6510)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813b6510-ffffffff813b6564: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c2f20)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813c2f20-ffffffff813c2f74: ext4_get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_get_bitmap(struct super_block *sb, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813d80d0)
Location: fs/ext4/resize.c:1262
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813d80d0-ffffffff813d8124: ext4_get_bitmap (STB_LOCAL)
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
