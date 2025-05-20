# Function: <code>__ext4_get_inode_loc_noinmem</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140dcc2)
Location: fs/ext4/inode.c:4435
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81413e86)
Location: fs/ext4/inode.c:4434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814630e0)
Location: fs/ext4/inode.c:4355
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff814630e0-ffffffff8146316b: __ext4_get_inode_loc_noinmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e2c30)
Location: fs/ext4/inode.c:4577
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff814e2c30-ffffffff814e2ccc: __ext4_get_inode_loc_noinmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157c0b0)
Location: fs/ext4/inode.c:4672
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff8157c0b0-ffffffff8157c14c: __ext4_get_inode_loc_noinmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b34c0)
Location: fs/ext4/inode.c:4457
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff815b34c0-ffffffff815b355c: __ext4_get_inode_loc_noinmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ec2d0)
Location: fs/ext4/inode.c:4476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff815ec2d0-ffffffff815ec36c: __ext4_get_inode_loc_noinmem (STB_LOCAL)
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
