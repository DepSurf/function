# Function: <code>add_new_gdb</code>

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
In fs/ext4/resize.c (ffffffff812c00f3)
Location: fs/ext4/resize.c:752
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
In fs/ext4/resize.c (ffffffff812ef4f4)
Location: fs/ext4/resize.c:752
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
In fs/ext4/resize.c (ffffffff813054c4)
Location: fs/ext4/resize.c:752
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
In fs/ext4/resize.c (ffffffff8131fa88)
Location: fs/ext4/resize.c:753
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
In fs/ext4/resize.c (ffffffff81344128)
Location: fs/ext4/resize.c:776
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
In fs/ext4/resize.c (ffffffff8137215d)
Location: fs/ext4/resize.c:779
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
In fs/ext4/resize.c (ffffffff8138a660)
Location: fs/ext4/resize.c:779
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:779
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff813b4d00-ffffffff813b513d: add_new_gdb (STB_LOCAL)
ffffffff813b796d-ffffffff813b7982: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff813ce7e0-ffffffff813cec1d: add_new_gdb (STB_LOCAL)
ffffffff813d0cb8-ffffffff813d0ccd: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:788
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff8141bb30-ffffffff8141bfa7: add_new_gdb (STB_LOCAL)
ffffffff8141d0f8-ffffffff8141d10d: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:788
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff8142f840-ffffffff8142fd12: add_new_gdb (STB_LOCAL)
ffffffff81bec5be-ffffffff81bec5d3: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:788
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81436530-ffffffff814369be: add_new_gdb (STB_LOCAL)
ffffffff81bde670-ffffffff81bde685: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:796
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8148a130-ffffffff8148a5e3: add_new_gdb (STB_LOCAL)
ffffffff81ccd3c3-ffffffff81ccd3f4: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:818
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8150dab0-ffffffff8150dfc2: add_new_gdb (STB_LOCAL)
ffffffff81e80304-ffffffff81e8033d: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:821
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff815a88f0-ffffffff815a8e17: add_new_gdb (STB_LOCAL)
ffffffff8207075d-ffffffff82070781: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:821
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff815df170-ffffffff815df679: add_new_gdb (STB_LOCAL)
ffffffff820f0424-ffffffff820f0440: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:818
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81617c50-ffffffff81618159: add_new_gdb (STB_LOCAL)
ffffffff821cd5f7-ffffffff821cd613: add_new_gdb.cold (STB_LOCAL)
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
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a7148)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffff8000104a7148-ffff8000104a7564: add_new_gdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0669270)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
c0669270-c06696e0: add_new_gdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d4a70)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
c0000000005d4a70-c0000000005d500c: add_new_gdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000327b6e)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffe000327b6e-ffffffe000327f06: add_new_gdb (STB_LOCAL)
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
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff813c6dc0-ffffffff813c71fd: add_new_gdb (STB_LOCAL)
ffffffff813c9298-ffffffff813c92ad: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff813b7840-ffffffff813b7c7d: add_new_gdb (STB_LOCAL)
ffffffff813b9d18-ffffffff813b9d2d: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff813c4250-ffffffff813c468d: add_new_gdb (STB_LOCAL)
ffffffff813c6728-ffffffff813c673d: add_new_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int add_new_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:806
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff813d9420-ffffffff813d9867: add_new_gdb (STB_LOCAL)
ffffffff813db958-ffffffff813db96d: add_new_gdb.cold (STB_LOCAL)
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
