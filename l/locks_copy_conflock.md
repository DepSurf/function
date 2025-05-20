# Function: <code>locks_copy_conflock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125eef0)
Location: fs/locks.c:321
Inline: False
Direct callers:
  - fs/locks.c:locks_copy_lock
  - fs/locks.c:posix_test_lock
  - fs/locks.c:__posix_lock_file
```
**Symbols:**

```
ffffffff8125eef0-ffffffff8125ef69: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128a940)
Location: fs/locks.c:348
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff8128a940-ffffffff8128a9b9: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8129f620)
Location: fs/locks.c:358
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff8129f620-ffffffff8129f699: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ae490)
Location: fs/locks.c:358
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff812ae490-ffffffff812ae50a: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d1ee0)
Location: fs/locks.c:375
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff812d1ee0-ffffffff812d1f57: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fca00)
Location: fs/locks.c:375
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff812fca00-ffffffff812fca76: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81312270)
Location: fs/locks.c:407
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff81312270-ffffffff813122f2: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81339740)
Location: fs/locks.c:408
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff81339740-ffffffff813397c1: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81351c90)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff81351c90-ffffffff81351d11: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139a5f1)
Location: fs/locks.c:409
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81398700-ffffffff81398781: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ac0b1)
Location: fs/locks.c:409
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff813aa1e0-ffffffff813aa261: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b3641)
Location: fs/locks.c:409
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff813b16a0-ffffffff813b1721: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81403321)
Location: fs/locks.c:409
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81401390-ffffffff81401411: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81477da0)
Location: fs/locks.c:361
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff814755d0-ffffffff81475666: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150a670)
Location: fs/locks.c:361
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff81507a90-ffffffff81507b26: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81541df0)
Location: fs/locks.c:362
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff8153f100-ffffffff8153f196: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81577320)
Location: fs/locks.c:361
Inline: True
Inline callers:
  - fs/locks.c:locks_copy_lock
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
```
**Symbols:**

```
ffffffff815745e0-ffffffff81574676: locks_copy_conflock (STB_GLOBAL)
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
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010413d58)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffff800010413d58-ffff800010413dd4: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05dffc0)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
c05dffc0-c05e003c: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000521fb0)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
c000000000521fb0-c00000000052204c: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bb6d0)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffe0002bb6d0-ffffffe0002bb73a: locks_copy_conflock (STB_GLOBAL)
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
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a270)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff8134a270-ffffffff8134a2f1: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133af50)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff8133af50-ffffffff8133afd1: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81347d40)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff81347d40-ffffffff81347dc1: locks_copy_conflock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void locks_copy_conflock(struct file_lock *new, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135b040)
Location: fs/locks.c:409
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_copy_lock
```
**Symbols:**

```
ffffffff8135b040-ffffffff8135b0c1: locks_copy_conflock (STB_GLOBAL)
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
