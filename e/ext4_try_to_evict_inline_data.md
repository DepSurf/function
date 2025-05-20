# Function: <code>ext4_try_to_evict_inline_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_try_to_evict_inline_data(handle_t *handle, struct inode *inode, int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e26c0)
Location: fs/ext4/inline.c:1865
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff812e26c0-ffffffff812e2788: ext4_try_to_evict_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_try_to_evict_inline_data(handle_t *handle, struct inode *inode, int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81312680)
Location: fs/ext4/inline.c:1863
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff81312680-ffffffff8131273b: ext4_try_to_evict_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_try_to_evict_inline_data(handle_t *handle, struct inode *inode, int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81328600)
Location: fs/ext4/inline.c:1880
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff81328600-ffffffff813286bb: ext4_try_to_evict_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_try_to_evict_inline_data(handle_t *handle, struct inode *inode, int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fc510)
Location: fs/ext4/inline.c:1879
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff812fc510-ffffffff812fc5cb: ext4_try_to_evict_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_try_to_evict_inline_data(handle_t *handle, struct inode *inode, int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81320d70)
Location: fs/ext4/inline.c:1902
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff81320d70-ffffffff81320e2b: ext4_try_to_evict_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
