# Function: <code>__locks_wake_up_blocks</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81313380)
Location: fs/locks.c:734
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81313380-ffffffff8131342c: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ac20)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff8133ac20-ffffffff8133acdd: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81353150)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81353150-ffffffff81353200: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81399e60)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81399e60-ffffffff81399f10: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ab950)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff813ab950-ffffffff813aba00: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b2ea0)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff813b2ea0-ffffffff813b2f50: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81402b90)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81402b90-ffffffff81402c40: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81477600)
Location: fs/locks.c:680
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81477600-ffffffff814776be: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509e40)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81509e40-ffffffff81509efe: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815415c0)
Location: fs/locks.c:667
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff815415c0-ffffffff8154167e: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81576aa0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81576aa0-ffffffff81576b5e: __locks_wake_up_blocks (STB_LOCAL)
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
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010414c00)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffff800010414c00-ffff800010414cc4: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1748)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
c05e1748-c05e1808: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000523e00)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
c000000000523e00-c000000000523f24: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc884)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffe0002bc884-ffffffe0002bc924: __locks_wake_up_blocks (STB_LOCAL)
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
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b730)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff8134b730-ffffffff8134b7e0: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c410)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff8133c410-ffffffff8133c4c0: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81349200)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff81349200-ffffffff813492b0: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c630)
Location: fs/locks.c:730
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_delete_block
```
**Symbols:**

```
ffffffff8135c630-ffffffff8135c6e0: __locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
