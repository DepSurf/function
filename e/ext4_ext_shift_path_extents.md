# Function: <code>ext4_ext_shift_path_extents</code>

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
In fs/ext4/extents.c (ffffffff812c49a6)
Location: fs/ext4/extents.c:5265
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff812f41f4)
Location: fs/ext4/extents.c:5267
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8130a191)
Location: fs/ext4/extents.c:5243
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff812e8870)
Location: fs/ext4/extents.c:5239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8130d310)
Location: fs/ext4/extents.c:5242
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8133c4f8)
Location: fs/ext4/extents.c:5238
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff81353ba8)
Location: fs/ext4/extents.c:5140
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8137d6e9)
Location: fs/ext4/extents.c:5150
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff81395e09)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e0600)
Location: fs/ext4/extents.c:4995
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff813e0600-ffffffff813e08ae: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f1e80)
Location: fs/ext4/extents.c:5004
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff813f1e80-ffffffff813f2135: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f8300)
Location: fs/ext4/extents.c:5010
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff813f8300-ffffffff813f85b4: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144a800)
Location: fs/ext4/extents.c:5018
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8144a800-ffffffff8144aa52: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c6fe0)
Location: fs/ext4/extents.c:5021
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff814c6fe0-ffffffff814c7229: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155f5f0)
Location: fs/ext4/extents.c:5025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8155f5f0-ffffffff8155f839: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81597360)
Location: fs/ext4/extents.c:5024
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff81597360-ffffffff815975b8: ext4_ext_shift_path_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_shift_path_extents(struct ext4_ext_path *path, ext4_lblk_t shift, struct inode *inode, handle_t *handle, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d0010)
Location: fs/ext4/extents.c:5059
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff815d0010-ffffffff815d0268: ext4_ext_shift_path_extents (STB_LOCAL)
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
In fs/ext4/extents.c (ffff800010468c50)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (c06299d4)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (c000000000587260)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffe0002f66c4)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8138e3e9)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8137ee79)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8138bd49)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
In fs/ext4/extents.c (ffffffff8139fa99)
Location: fs/ext4/extents.c:5228
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
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
