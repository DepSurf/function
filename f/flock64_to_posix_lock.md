# Function: <code>flock64_to_posix_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125ef70)
Location: fs/locks.c:410
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8125ef70-ffffffff8125f0b2: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128a9c0)
Location: fs/locks.c:437
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8128a9c0-ffffffff8128aafd: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8129f6a0)
Location: fs/locks.c:447
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8129f6a0-ffffffff8129f7dd: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ae510)
Location: fs/locks.c:447
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812ae510-ffffffff812ae646: flock64_to_posix_lock (STB_LOCAL)
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
In fs/locks.c (ffffffff812d1f71)
Location: fs/locks.c:464
Inline: True
Inline callers:
  - fs/locks.c:flock_to_posix_lock
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
In fs/locks.c (ffffffff812fcaf5)
Location: fs/locks.c:464
Inline: True
Inline callers:
  - fs/locks.c:flock_to_posix_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81312360)
Location: fs/locks.c:516
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81312360-ffffffff813124a9: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813397d0)
Location: fs/locks.c:517
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813397d0-ffffffff8133992b: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81351d20)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81351d20-ffffffff81351e7b: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81398790)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81398790-ffffffff813988ec: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aa270)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813aa270-ffffffff813aa3cc: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b1730)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813b1730-ffffffff813b1888: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81401420)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81401420-ffffffff81401578: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81475710)
Location: fs/locks.c:468
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81475710-ffffffff81475889: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81507bf0)
Location: fs/locks.c:454
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81507bf0-ffffffff81507d69: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8153f260)
Location: fs/locks.c:455
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8153f260-ffffffff8153f3dc: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81574740)
Location: fs/locks.c:454
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81574740-ffffffff815748ba: flock64_to_posix_lock (STB_LOCAL)
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
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010413dd8)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffff800010413dd8-ffff800010413f24: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e0e34)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:flock_to_posix_lock
```
**Symbols:**

```
c05e0e34-c05e106c: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000522050)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
c000000000522050-c000000000522198: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bb73a)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffe0002bb73a-ffffffe0002bb82a: flock64_to_posix_lock (STB_LOCAL)
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
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a300)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8134a300-ffffffff8134a45b: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133afe0)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8133afe0-ffffffff8133b13b: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81347dd0)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81347dd0-ffffffff81347f2b: flock64_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int flock64_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock64 *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135b170)
Location: fs/locks.c:518
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8135b170-ffffffff8135b2cb: flock64_to_posix_lock (STB_LOCAL)
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
