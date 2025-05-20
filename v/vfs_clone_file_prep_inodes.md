# Function: <code>vfs_clone_file_prep_inodes</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_clone_file_prep_inodes(struct inode *inode_in, loff_t pos_in, struct inode *inode_out, loff_t pos_out, u64 *len, bool is_dedupe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244920)
Location: fs/read_write.c:1700
Inline: False
```
**Symbols:**

```
ffffffff81244920-ffffffff81244b68: vfs_clone_file_prep_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_clone_file_prep_inodes(struct inode *inode_in, loff_t pos_in, struct inode *inode_out, loff_t pos_out, u64 *len, bool is_dedupe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250290)
Location: fs/read_write.c:1716
Inline: False
```
**Symbols:**

```
ffffffff81250290-ffffffff812504ba: vfs_clone_file_prep_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_clone_file_prep_inodes(struct inode *inode_in, loff_t pos_in, struct inode *inode_out, loff_t pos_out, u64 *len, bool is_dedupe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272240)
Location: fs/read_write.c:1719
Inline: False
```
**Symbols:**

```
ffffffff81272240-ffffffff8127246a: vfs_clone_file_prep_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_clone_file_prep_inodes(struct inode *inode_in, loff_t pos_in, struct inode *inode_out, loff_t pos_out, u64 *len, bool is_dedupe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298270)
Location: fs/read_write.c:1746
Inline: False
```
**Symbols:**

```
ffffffff81298270-ffffffff8129849e: vfs_clone_file_prep_inodes (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
