# Function: <code>filename_parentat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c050)
Location: fs/namei.c:2198
Inline: False
Direct callers:
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:kern_path_locked
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
```
**Symbols:**

```
ffffffff8121c050-ffffffff8121c1de: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812434d0)
Location: fs/namei.c:2335
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812434d0-ffffffff8124365e: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256450)
Location: fs/namei.c:2324
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81256450-ffffffff812565de: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812625e0)
Location: fs/namei.c:2369
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812625e0-ffffffff81262770: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81284e30)
Location: fs/namei.c:2367
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81284e30-ffffffff81284fc0: filename_parentat (STB_LOCAL)
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
In fs/namei.c (ffffffff812ac79a)
Location: fs/namei.c:2354
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812abf80-ffffffff812ac0f4: filename_parentat.isra.57.part.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812c189a)
Location: fs/namei.c:2378
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812c1080-ffffffff812c11f4: filename_parentat.isra.58.part.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812dd860)
Location: fs/namei.c:2376
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812dd860-ffffffff812dd9df: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812ef390)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812ef390-ffffffff812ef50f: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813273a0)
Location: fs/namei.c:2397
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff813273a0-ffffffff81327555: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813327b0)
Location: fs/namei.c:2395
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff813327b0-ffffffff81332965: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81338800)
Location: fs/namei.c:2485
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81338800-ffffffff813389c8: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81382bb0)
Location: fs/namei.c:2509
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81382bb0-ffffffff81382d84: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81406080)
Location: fs/namei.c:2555
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81406080-ffffffff8140627a: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814903d0)
Location: fs/namei.c:2534
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff814903d0-ffffffff814905ca: filename_parentat (STB_LOCAL)
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
In fs/namei.c (ffffffff814c8b4b)
Location: fs/namei.c:2564
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
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
In fs/namei.c (ffffffff814fb3fb)
Location: fs/namei.c:2571
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:__kern_path_locked
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffff800010398b48)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffff800010398b48-ffff800010398ca8: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f1e4)
Location: fs/namei.c:2369
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
c057f1e4-c057f354: filename_parentat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (c000000000493060)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
c000000000493060-c000000000493244: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct filename *filename_parentat(int dfd, struct filename *name, unsigned int flags, struct path *parent, struct qstr *last, int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266744)
Location: fs/namei.c:2369
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffe000266744-ffffffe00026684c: filename_parentat (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812e7970)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812e7970-ffffffff812e7aef: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812d85b0)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812d85b0-ffffffff812d872f: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812e5780)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812e5780-ffffffff812e58ff: filename_parentat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812f6700)
Location: fs/namei.c:2369
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812f6700-ffffffff812f687f: filename_parentat.isra.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct filename *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
