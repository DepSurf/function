# Function: <code>do_lock_file_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812614a0)
Location: fs/locks.c:2113
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff812614a0-ffffffff81261592: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d630)
Location: fs/locks.c:2139
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8128d630-ffffffff8128d72a: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2bc0)
Location: fs/locks.c:2177
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff812a2bc0-ffffffff812a2c96: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b1da0)
Location: fs/locks.c:2168
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff812b1da0-ffffffff812b1e72: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d5900)
Location: fs/locks.c:2204
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff812d5900-ffffffff812d59d2: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8130119b)
Location: fs/locks.c:2209
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff813003c0-ffffffff81300482: do_lock_file_wait.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316090)
Location: fs/locks.c:2323
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff81316090-ffffffff8131616a: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d870)
Location: fs/locks.c:2341
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8133d870-ffffffff8133d94c: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355e20)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff81355e20-ffffffff81355f0b: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139d360)
Location: fs/locks.c:2433
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8139d360-ffffffff8139d471: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aed30)
Location: fs/locks.c:2434
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff813aed30-ffffffff813aee41: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b6090)
Location: fs/locks.c:2436
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff813b6090-ffffffff813b61a1: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81405d90)
Location: fs/locks.c:2339
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff81405d90-ffffffff81405ea1: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81479580)
Location: fs/locks.c:2325
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff81479580-ffffffff814796ec: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150bee0)
Location: fs/locks.c:2307
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8150bee0-ffffffff8150c062: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81543660)
Location: fs/locks.c:2284
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff81543660-ffffffff815437d9: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81578b60)
Location: fs/locks.c:2294
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff81578b60-ffffffff81578cd9: do_lock_file_wait (STB_LOCAL)
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
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418948)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffff800010418948-ffff800010418a64: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e3358)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
c05e3358-c05e3458: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005264d0)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
c0000000005264d0-c00000000052664c: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf374)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffe0002bf374-ffffffe0002bf44a: do_lock_file_wait (STB_LOCAL)
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
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e400)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8134e400-ffffffff8134e4eb: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133f0e0)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8133f0e0-ffffffff8133f1cb: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134bed0)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8134bed0-ffffffff8134bfbb: do_lock_file_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_lock_file_wait(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135dd30)
Location: fs/locks.c:2430
Inline: True
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8135dd30-ffffffff8135de16: do_lock_file_wait (STB_LOCAL)
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
