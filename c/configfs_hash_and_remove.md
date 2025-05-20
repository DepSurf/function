# Function: <code>configfs_hash_and_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff812de2e0)
Location: fs/configfs/inode.c:259
Inline: False
```
**Symbols:**

```
ffffffff812de2e0-ffffffff812de3db: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81302c20)
Location: fs/configfs/inode.c:259
Inline: False
```
**Symbols:**

```
ffffffff81302c20-ffffffff81302d1b: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81330b70)
Location: fs/configfs/inode.c:259
Inline: False
```
**Symbols:**

```
ffffffff81330b70-ffffffff81330c69: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81347f60)
Location: fs/configfs/inode.c:259
Inline: False
```
**Symbols:**

```
ffffffff81347f60-ffffffff81348059: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/inode.c (0)
Location: fs/configfs/inode.c:245
Inline: False
```
**Symbols:**

```
ffffffff813704f8-ffffffff8137050b: configfs_hash_and_remove.cold (STB_LOCAL)
ffffffff813703f0-ffffffff813704f8: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813888e0)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff813888e0-ffffffff813889e8: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813d3620)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff813d3620-ffffffff813d3728: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813e5360)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff813e5360-ffffffff813e5468: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813ebf70)
Location: fs/configfs/inode.c:227
Inline: False
```
**Symbols:**

```
ffffffff813ebf70-ffffffff813ec078: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8143dd10)
Location: fs/configfs/inode.c:221
Inline: False
```
**Symbols:**

```
ffffffff8143dd10-ffffffff8143de33: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff814b9600)
Location: fs/configfs/inode.c:221
Inline: False
```
**Symbols:**

```
ffffffff814b9600-ffffffff814b9741: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81550d90)
Location: fs/configfs/inode.c:221
Inline: False
```
**Symbols:**

```
ffffffff81550d90-ffffffff81550ed1: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81588a70)
Location: fs/configfs/inode.c:221
Inline: False
```
**Symbols:**

```
ffffffff81588a70-ffffffff81588bb1: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815c1640)
Location: fs/configfs/inode.c:220
Inline: False
```
**Symbols:**

```
ffffffff815c1640-ffffffff815c1784: configfs_hash_and_remove (STB_GLOBAL)
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
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffff800010458be8)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffff800010458be8-ffff800010458d68: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c061a950)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
c061a950-c061aaa8: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c0000000005736f0)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
c0000000005736f0-c000000000573a5c: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffe0002e9bf4)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffe0002e9bf4-ffffffe0002e9d34: configfs_hash_and_remove (STB_GLOBAL)
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
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81380ec0)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff81380ec0-ffffffff81380fc8: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81371950)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff81371950-ffffffff81371a58: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8137e990)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff8137e990-ffffffff8137ea98: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void configfs_hash_and_remove(struct dentry *dir, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81392490)
Location: fs/configfs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff81392490-ffffffff81392596: configfs_hash_and_remove (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
