# Function: <code>inode_update_time</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int inode_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395189)
Location: fs/inode.c:1785
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81394ab0-ffffffff81394ad7: inode_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int inode_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417fde)
Location: fs/inode.c:1866
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81416d70-ffffffff81416dab: inode_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int inode_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a3860)
Location: fs/inode.c:1868
Inline: True
Inline callers:
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814a1dd0-ffffffff814a1e0b: inode_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int inode_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d89dc)
Location: fs/inode.c:1912
Inline: True
Inline callers:
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814d6f10-ffffffff814d6f4b: inode_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int inode_update_time(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150b149)
Location: fs/inode.c:1914
Inline: True
Inline callers:
  - fs/inode.c:kiocb_modified
  - fs/inode.c:file_modified
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81509fe0-ffffffff8150a019: inode_update_time (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct timespec64 *time</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, time, flags</code> ➡️ <code>inode, flags</code>
</li>
</ul>
</details>
</li>
</ul>
