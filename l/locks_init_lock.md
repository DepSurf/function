# Function: <code>locks_init_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125f7a0)
Location: fs/locks.c:310
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8125f7a0-ffffffff8125f81b: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128b9f0)
Location: fs/locks.c:337
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff8128b9f0-ffffffff8128ba6b: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a07f0)
Location: fs/locks.c:347
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812a07f0-ffffffff812a086b: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812af630)
Location: fs/locks.c:347
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812af630-ffffffff812af6ab: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d30b0)
Location: fs/locks.c:364
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812d30b0-ffffffff812d312b: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fd9a0)
Location: fs/locks.c:364
Inline: False
Direct callers:
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff812fd9a0-ffffffff812fda1c: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81313240)
Location: fs/locks.c:397
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff81313240-ffffffff813132c8: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133aae0)
Location: fs/locks.c:398
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8133aae0-ffffffff8133ab68: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81353010)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff81353010-ffffffff81353098: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139c211)
Location: fs/locks.c:399
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff813996b0-ffffffff81399728: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813adc11)
Location: fs/locks.c:399
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
```
**Symbols:**

```
ffffffff813ab190-ffffffff813ab208: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5151)
Location: fs/locks.c:399
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff813b2660-ffffffff813b26d8: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81404e51)
Location: fs/locks.c:399
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81402160-ffffffff814021d8: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81476ec0)
Location: fs/locks.c:351
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81476ec0-ffffffff81476f46: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509150)
Location: fs/locks.c:351
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff81509150-ffffffff815091d6: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81540710)
Location: fs/locks.c:352
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff81540710-ffffffff81540796: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81575bf0)
Location: fs/locks.c:351
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:__do_sys_flock
```
**Symbols:**

```
ffffffff81575bf0-ffffffff81575c76: locks_init_lock (STB_GLOBAL)
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
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010414ab0)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffff800010414ab0-ffff800010414b40: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1588)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
c05e1588-c05e15ec: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000523c50)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
c000000000523c50-c000000000523cd8: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc774)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffe0002bc774-ffffffe0002bc7d8: locks_init_lock (STB_GLOBAL)
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
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b5f0)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8134b5f0-ffffffff8134b678: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c2d0)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8133c2d0-ffffffff8133c358: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813490c0)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff813490c0-ffffffff81349148: locks_init_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void locks_init_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c4f0)
Location: fs/locks.c:399
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:flock_make_lock
```
**Symbols:**

```
ffffffff8135c4f0-ffffffff8135c578: locks_init_lock (STB_GLOBAL)
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
