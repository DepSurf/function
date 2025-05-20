# Function: <code>flock_to_posix_lock</code>

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
In fs/locks.c (ffffffff81262a4d)
Location: fs/locks.c:460
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlk
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
In fs/locks.c (ffffffff8128ee63)
Location: fs/locks.c:487
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff812a3e17)
Location: fs/locks.c:497
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff812b2a36)
Location: fs/locks.c:497
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int flock_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d1f60)
Location: fs/locks.c:514
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812d1f60-ffffffff812d207e: flock_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int flock_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fcae0)
Location: fs/locks.c:514
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812fcae0-ffffffff812fcbfe: flock_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316c25)
Location: fs/locks.c:566
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e4c4)
Location: fs/locks.c:567
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81356ab4)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139dd52)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af701)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff813b69bc)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814066bc)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff8147b1b4)
Location: fs/locks.c:518
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff8150dd34)
Location: fs/locks.c:504
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff8154551f)
Location: fs/locks.c:505
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
In fs/locks.c (ffffffff8157aa7f)
Location: fs/locks.c:504
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104195c4)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int flock_to_posix_lock(struct file *filp, struct file_lock *fl, struct flock *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e106c)
Location: fs/locks.c:568
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
c05e106c-c05e10f0: flock_to_posix_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005290d8)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bfd8c)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134f094)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133fd74)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134cb64)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813600a4)
Location: fs/locks.c:568
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
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
</ul>
<b>Arch</b>
<ul>
</ul>
