# Function: <code>flock_locks_conflict</code>

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
In fs/locks.c (ffffffff81260f30)
Location: fs/locks.c:749
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
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
In fs/locks.c (ffffffff8128c741)
Location: fs/locks.c:776
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
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
In fs/locks.c (ffffffff812a17ce)
Location: fs/locks.c:796
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
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
In fs/locks.c (ffffffff812b066e)
Location: fs/locks.c:796
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d40ee)
Location: fs/locks.c:808
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ff38c)
Location: fs/locks.c:808
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81315342)
Location: fs/locks.c:917
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813124b0-ffffffff813124eb: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133cbb3)
Location: fs/locks.c:913
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81339930-ffffffff8133996b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355163)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81351e80-ffffffff81351ebb: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139bf46)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813988f0-ffffffff8139892b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ad940)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813aa3d0-ffffffff813aa40b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b4e8e)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813b1890-ffffffff813b18cb: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81404b8e)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81401580-ffffffff814015bb: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147a1d5)
Location: fs/locks.c:887
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81475890-ffffffff814758cb: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150cba5)
Location: fs/locks.c:873
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81507d80-ffffffff81507dbb: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81544345)
Location: fs/locks.c:874
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8153f3f0-ffffffff8153f42b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81579835)
Location: fs/locks.c:888
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff815748d0-ffffffff8157490b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010417be0)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffff800010413f28-ffff800010413f94: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e3ce8)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c05e00b8-c05e0110: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000527868)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c0000000005221a0-c0000000005221f8: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002be8da)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffe0002bb82a-ffffffe0002bb88c: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134d743)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8134a460-ffffffff8134a49b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e423)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133b140-ffffffff8133b17b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b213)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81347f30-ffffffff81347f6b: flock_locks_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool flock_locks_conflict(struct file_lock *caller_fl, struct file_lock *sys_fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135e63a)
Location: fs/locks.c:937
Inline: True
Inline callers:
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8135b340-ffffffff8135b37b: flock_locks_conflict (STB_LOCAL)
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
