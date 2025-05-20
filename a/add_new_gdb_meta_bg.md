# Function: <code>add_new_gdb_meta_bg</code>

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
In fs/ext4/resize.c (ffffffff812bffbe)
Location: fs/ext4/resize.c:882
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/resize.c (ffffffff812ef503)
Location: fs/ext4/resize.c:882
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/resize.c (ffffffff813054d3)
Location: fs/ext4/resize.c:882
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/resize.c (ffffffff8131f95a)
Location: fs/ext4/resize.c:883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff81343ffa)
Location: fs/ext4/resize.c:907
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff81372004)
Location: fs/ext4/resize.c:910
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff8138a514)
Location: fs/ext4/resize.c:907
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b5aa1)
Location: fs/ext4/resize.c:908
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813cec87)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141a4c0)
Location: fs/ext4/resize.c:918
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff8141a4c0-ffffffff8141a656: add_new_gdb_meta_bg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142e6a0)
Location: fs/ext4/resize.c:923
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff8142e6a0-ffffffff8142e83b: add_new_gdb_meta_bg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff814363c0)
Location: fs/ext4/resize.c:923
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff814363c0-ffffffff81436526: add_new_gdb_meta_bg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:932
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81489fa0-ffffffff8148a123: add_new_gdb_meta_bg (STB_LOCAL)
ffffffff81ccd386-ffffffff81ccd3c3: add_new_gdb_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:954
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8150cf80-ffffffff8150d123: add_new_gdb_meta_bg (STB_LOCAL)
ffffffff81e8026c-ffffffff81e802a8: add_new_gdb_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:957
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff815a7ca0-ffffffff815a7e43: add_new_gdb_meta_bg (STB_LOCAL)
ffffffff820706fa-ffffffff82070736: add_new_gdb_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:957
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff815de510-ffffffff815de6cb: add_new_gdb_meta_bg (STB_LOCAL)
ffffffff820f03c5-ffffffff820f03fd: add_new_gdb_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_new_gdb_meta_bg(struct super_block *sb, handle_t *handle, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81616fc0)
Location: fs/ext4/resize.c:960
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81616fc0-ffffffff8161715d: add_new_gdb_meta_bg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a75ec)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c066975c)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d52b0)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000328036)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/resize.c (ffffffff813c7267)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813b7ce7)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813c46f7)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813d98d7)
Location: fs/ext4/resize.c:937
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
