# Function: <code>ext4_iomap_overwrite_begin</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9b00)
Location: fs/ext4/inode.c:3452
Inline: True
```
**Symbols:**

```
ffffffff813f9b00-ffffffff813f9b2a: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c120)
Location: fs/ext4/inode.c:3490
Inline: True
```
**Symbols:**

```
ffffffff8140c120-ffffffff8140c14a: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814122a0)
Location: fs/ext4/inode.c:3489
Inline: True
```
**Symbols:**

```
ffffffff814122a0-ffffffff814122ca: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81465080)
Location: fs/ext4/inode.c:3412
Inline: False
```
**Symbols:**

```
ffffffff81465080-ffffffff814650aa: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e4960)
Location: fs/ext4/inode.c:3475
Inline: False
```
**Symbols:**

```
ffffffff814e4960-ffffffff814e49ae: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157ded0)
Location: fs/ext4/inode.c:3563
Inline: False
```
**Symbols:**

```
ffffffff8157ded0-ffffffff8157df1e: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b51e0)
Location: fs/ext4/inode.c:3346
Inline: False
```
**Symbols:**

```
ffffffff815b51e0-ffffffff815b521a: ext4_iomap_overwrite_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_iomap_overwrite_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815edf80)
Location: fs/ext4/inode.c:3388
Inline: False
```
**Symbols:**

```
ffffffff815edf80-ffffffff815edfba: ext4_iomap_overwrite_begin (STB_LOCAL)
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
