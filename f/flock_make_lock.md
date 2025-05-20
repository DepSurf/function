# Function: <code>flock_make_lock</code>

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
In fs/locks.c (ffffffff812628d1)
Location: fs/locks.c:374
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
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
In fs/locks.c (ffffffff8128ead5)
Location: fs/locks.c:401
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
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
In fs/locks.c (ffffffff812a3a66)
Location: fs/locks.c:411
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
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
In fs/locks.c (ffffffff812b26fc)
Location: fs/locks.c:411
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
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
In fs/locks.c (ffffffff812d625c)
Location: fs/locks.c:428
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
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
In fs/locks.c (ffffffff81300af1)
Location: fs/locks.c:428
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813132d0)
Location: fs/locks.c:477
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813132d0-ffffffff81313375: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ab70)
Location: fs/locks.c:478
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8133ab70-ffffffff8133ac15: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813530a0)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813530a0-ffffffff81353145: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139c211)
Location: fs/locks.c:479
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8139a950-ffffffff8139aa68: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813adc11)
Location: fs/locks.c:479
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813ac410-ffffffff813ac528: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5151)
Location: fs/locks.c:479
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff813b3710-ffffffff813b3828: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81404e51)
Location: fs/locks.c:479
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff814033f0-ffffffff81403508: flock_make_lock (STB_LOCAL)
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
In fs/locks.c (ffffffff8147a520)
Location: fs/locks.c:429
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__do_sys_flock
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
In fs/locks.c (ffffffff8150cf00)
Location: fs/locks.c:428
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__do_sys_flock
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
In fs/locks.c (ffffffff815446a3)
Location: fs/locks.c:429
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__do_sys_flock
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
In fs/locks.c (ffffffff81579b93)
Location: fs/locks.c:428
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__do_sys_flock
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
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010414b40)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__arm64_sys_flock
```
**Symbols:**

```
ffff800010414b40-ffff800010414c00: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e15ec)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
c05e15ec-c05e16ac: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000523ce0)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
c000000000523ce0-c000000000523dfc: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc7d8)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__se_sys_flock
```
**Symbols:**

```
ffffffe0002bc7d8-ffffffe0002bc884: flock_make_lock (STB_LOCAL)
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
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b680)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8134b680-ffffffff8134b725: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c360)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8133c360-ffffffff8133c405: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81349150)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81349150-ffffffff813491f5: flock_make_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file_lock *flock_make_lock(struct file *filp, unsigned int cmd, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c580)
Location: fs/locks.c:479
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8135c580-ffffffff8135c625: flock_make_lock (STB_LOCAL)
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
