# Function: <code>locks_insert_global_locks</code>

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
In fs/locks.c (ffffffff8125f998)
Location: fs/locks.c:561
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
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
In fs/locks.c (ffffffff8128bb38)
Location: fs/locks.c:588
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
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
In fs/locks.c (ffffffff8129f89c)
Location: fs/locks.c:598
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
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
In fs/locks.c (ffffffff812ae70c)
Location: fs/locks.c:598
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2080)
Location: fs/locks.c:615
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812d2080-ffffffff812d20e5: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fe530)
Location: fs/locks.c:615
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812fe530-ffffffff812fe595: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81313fe0)
Location: fs/locks.c:667
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81313fe0-ffffffff81314045: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133b8d0)
Location: fs/locks.c:665
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133b8d0-ffffffff8133b933: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81353e20)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81353e20-ffffffff81353e83: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139a6f0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8139a6f0-ffffffff8139a753: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ac1b0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813ac1b0-ffffffff813ac213: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5836)
Location: fs/locks.c:666
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813b3860-ffffffff813b38c3: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8140555e)
Location: fs/locks.c:666
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81403540-ffffffff814035a3: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81479c1f)
Location: fs/locks.c:616
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c5bf)
Location: fs/locks.c:602
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81543d34)
Location: fs/locks.c:603
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157921c)
Location: fs/locks.c:602
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
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
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416360)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffff800010416360-ffff800010416414: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e003c)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c05e003c-c05e00b8: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005251a0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c0000000005251a0-c0000000005252a4: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bd4bc)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffe0002bd4bc-ffffffe0002bd562: locks_insert_global_locks (STB_LOCAL)
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
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c400)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8134c400-ffffffff8134c463: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d0e0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133d0e0-ffffffff8133d143: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81349ed0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81349ed0-ffffffff81349f33: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void locks_insert_global_locks(struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135b2d0)
Location: fs/locks.c:666
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8135b2d0-ffffffff8135b331: locks_insert_global_locks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
