# Function: <code>ext4_ext_insert_index</code>

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
In fs/ext4/extents.c (ffffffff812c5d83)
Location: fs/ext4/extents.c:948
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
In fs/ext4/extents.c (ffffffff812f5614)
Location: fs/ext4/extents.c:954
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
In fs/ext4/extents.c (ffffffff8130b5c4)
Location: fs/ext4/extents.c:954
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
In fs/ext4/extents.c (ffffffff812e9cb4)
Location: fs/ext4/extents.c:954
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
In fs/ext4/extents.c (ffffffff8130e750)
Location: fs/ext4/extents.c:954
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
In fs/ext4/extents.c (ffffffff8133a7b9)
Location: fs/ext4/extents.c:948
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff81351b3c)
Location: fs/ext4/extents.c:948
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff8137b40d)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff813938dd)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813de290)
Location: fs/ext4/extents.c:927
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff813de290-ffffffff813de4b0: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813efb60)
Location: fs/ext4/extents.c:925
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff813efb60-ffffffff813efd80: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f6440)
Location: fs/ext4/extents.c:926
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff813f6440-ffffffff813f6660: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81447f00)
Location: fs/ext4/extents.c:964
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff81447f00-ffffffff814480f3: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c43f0)
Location: fs/ext4/extents.c:966
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff814c43f0-ffffffff814c4608: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155cae0)
Location: fs/ext4/extents.c:974
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff8155cae0-ffffffff8155ccf8: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815948e0)
Location: fs/ext4/extents.c:974
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff815948e0-ffffffff81594b1d: ext4_ext_insert_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_insert_index(handle_t *handle, struct inode *inode, struct ext4_ext_path *curp, int logical, ext4_fsblk_t ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cd5d0)
Location: fs/ext4/extents.c:974
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_split
```
**Symbols:**

```
ffffffff815cd5d0-ffffffff815cd7c4: ext4_ext_insert_index (STB_LOCAL)
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
In fs/ext4/extents.c (ffff8000104665a4)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (c0627078)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (c000000000584400)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffe0002f46ac)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff8138bebd)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff8137c94d)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff8138981d)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
In fs/ext4/extents.c (ffffffff8139d52b)
Location: fs/ext4/extents.c:952
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
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
