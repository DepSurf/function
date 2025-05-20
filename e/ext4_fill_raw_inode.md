# Function: <code>ext4_fill_raw_inode</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_fill_raw_inode(struct inode *inode, struct ext4_inode *raw_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4340
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff814e22e0-ffffffff814e27c0: ext4_fill_raw_inode (STB_LOCAL)
ffffffff81e7d86b-ffffffff81e7d888: ext4_fill_raw_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_fill_raw_inode(struct inode *inode, struct ext4_inode *raw_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4427
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff8157b6d0-ffffffff8157bbb0: ext4_fill_raw_inode (STB_LOCAL)
ffffffff8206ddd5-ffffffff8206ddf2: ext4_fill_raw_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_fill_raw_inode(struct inode *inode, struct ext4_inode *raw_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4212
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff815b2ad0-ffffffff815b2fa8: ext4_fill_raw_inode (STB_LOCAL)
ffffffff820edac4-ffffffff820edae1: ext4_fill_raw_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_fill_raw_inode(struct inode *inode, struct ext4_inode *raw_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4231
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff815eb8d0-ffffffff815ebd9e: ext4_fill_raw_inode (STB_LOCAL)
ffffffff821cabf3-ffffffff821cac10: ext4_fill_raw_inode.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
