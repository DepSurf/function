# Function: <code>ext4_ext_grow_indepth</code>

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
In fs/ext4/extents.c (ffffffff812c4f15)
Location: fs/ext4/extents.c:1265
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff812f476f)
Location: fs/ext4/extents.c:1271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff8130a71f)
Location: fs/ext4/extents.c:1271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff812e8d0f)
Location: fs/ext4/extents.c:1271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff8130d7af)
Location: fs/ext4/extents.c:1271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff8133cac7)
Location: fs/ext4/extents.c:1265
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff81354177)
Location: fs/ext4/extents.c:1265
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff8137c977)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (ffffffff81395077)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ddc80)
Location: fs/ext4/extents.c:1260
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff813ddc80-ffffffff813ddedd: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ef570)
Location: fs/ext4/extents.c:1258
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff813ef570-ffffffff813ef7cd: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f5a30)
Location: fs/ext4/extents.c:1261
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813f5a30-ffffffff813f5c8c: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81448290)
Location: fs/ext4/extents.c:1301
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81448290-ffffffff81448510: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c47d0)
Location: fs/ext4/extents.c:1303
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff814c47d0-ffffffff814c4a47: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155cd10)
Location: fs/ext4/extents.c:1311
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8155cd10-ffffffff8155cf8f: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81594b30)
Location: fs/ext4/extents.c:1311
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81594b30-ffffffff81594daf: ext4_ext_grow_indepth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_grow_indepth(handle_t *handle, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cd7e0)
Location: fs/ext4/extents.c:1311
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff815cd7e0-ffffffff815cda5f: ext4_ext_grow_indepth (STB_LOCAL)
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
In fs/ext4/extents.c (ffff800010467ddc)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (c0628ac4)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (c000000000587bc8)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffe0002f5aba)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (ffffffff8138d657)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (ffffffff8137e0e7)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (ffffffff8138afb7)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
In fs/ext4/extents.c (ffffffff8139ecf7)
Location: fs/ext4/extents.c:1279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
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
