# Function: <code>locks_alloc_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125f730)
Location: fs/locks.c:256
Inline: False
Direct callers:
  - fs/locks.c:lease_alloc
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:SyS_flock
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8125f730-ffffffff8125f798: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128b830)
Location: fs/locks.c:283
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff8128b830-ffffffff8128b898: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a0630)
Location: fs/locks.c:293
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff812a0630-ffffffff812a0698: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812af470)
Location: fs/locks.c:293
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff812af470-ffffffff812af4dc: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2ef0)
Location: fs/locks.c:310
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff812d2ef0-ffffffff812d2f5c: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fd7e0)
Location: fs/locks.c:310
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff812fd7e0-ffffffff812fd848: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81313060)
Location: fs/locks.c:342
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff81313060-ffffffff813130d4: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133a860)
Location: fs/locks.c:343
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8133a860-ffffffff8133a8df: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81352d90)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff81352d90-ffffffff81352e0f: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139dccd)
Location: fs/locks.c:344
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff81399dd0-ffffffff81399e51: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af67d)
Location: fs/locks.c:344
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff813ab8c0-ffffffff813ab941: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b693d)
Location: fs/locks.c:344
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff813b2e10-ffffffff813b2e91: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8140663d)
Location: fs/locks.c:344
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff81402b00-ffffffff81402b81: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147b13d)
Location: fs/locks.c:268
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81477570-ffffffff814775f1: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150dcbd)
Location: fs/locks.c:268
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81509da0-ffffffff81509e21: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8154549d)
Location: fs/locks.c:269
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81541520-ffffffff815415a1: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a9fd)
Location: fs/locks.c:268
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81576a00-ffffffff81576a81: locks_alloc_lock (STB_GLOBAL)
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
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104147f8)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffff8000104147f8-ffff800010414874: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e12e4)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
c05e12e4-c05e1364: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000523ab0)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
c000000000523ab0-c000000000523b50: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc544)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffe0002bc544-ffffffe0002bc5ba: locks_alloc_lock (STB_GLOBAL)
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
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b370)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8134b370-ffffffff8134b3ef: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c050)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8133c050-ffffffff8133c0cf: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81348e40)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff81348e40-ffffffff81348ebf: locks_alloc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file_lock *locks_alloc_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c270)
Location: fs/locks.c:344
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8135c270-ffffffff8135c2ef: locks_alloc_lock (STB_GLOBAL)
```
</details>
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
