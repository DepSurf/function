# Function: <code>ext4_iomap_xattr_begin</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd740)
Location: fs/ext4/extents.c:4845
Inline: False
```
**Symbols:**

```
ffffffff813dd740-ffffffff813dd84a: ext4_iomap_xattr_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ef030)
Location: fs/ext4/extents.c:4854
Inline: False
```
**Symbols:**

```
ffffffff813ef030-ffffffff813ef13a: ext4_iomap_xattr_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f54f0)
Location: fs/ext4/extents.c:4860
Inline: False
```
**Symbols:**

```
ffffffff813f54f0-ffffffff813f55fe: ext4_iomap_xattr_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4898
Inline: False
```
**Symbols:**

```
ffffffff81447c10-ffffffff81447d38: ext4_iomap_xattr_begin (STB_LOCAL)
ffffffff81cc8f66-ffffffff81cc8f9f: ext4_iomap_xattr_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4901
Inline: False
```
**Symbols:**

```
ffffffff814c3820-ffffffff814c396f: ext4_iomap_xattr_begin (STB_LOCAL)
ffffffff81e7bc17-ffffffff81e7bc50: ext4_iomap_xattr_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4905
Inline: False
```
**Symbols:**

```
ffffffff8155bb50-ffffffff8155bc9f: ext4_iomap_xattr_begin (STB_LOCAL)
ffffffff8206c29c-ffffffff8206c2d5: ext4_iomap_xattr_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4904
Inline: False
```
**Symbols:**

```
ffffffff81593970-ffffffff81593abf: ext4_iomap_xattr_begin (STB_LOCAL)
ffffffff820ec12e-ffffffff820ec167: ext4_iomap_xattr_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_xattr_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4939
Inline: False
```
**Symbols:**

```
ffffffff815cc660-ffffffff815cc7af: ext4_iomap_xattr_begin (STB_LOCAL)
ffffffff821c9366-ffffffff821c939f: ext4_iomap_xattr_begin.cold (STB_LOCAL)
```
</details>
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
