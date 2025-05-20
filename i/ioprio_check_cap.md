# Function: <code>ioprio_check_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8149a750)
Location: block/ioprio.c:64
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff8149a750-ffffffff8149a7b2: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814b4a60)
Location: block/ioprio.c:64
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814b4a60-ffffffff814b4ac2: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814e2fa0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814e2fa0-ffffffff814e3001: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814fc360)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814fc360-ffffffff814fc3c1: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8155bd60)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff8155bd60-ffffffff8155bdc7: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81577eb0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff81577eb0-ffffffff81577f23: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8157fbf0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff8157fbf0-ffffffff8157fc63: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff815e4ed0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff815e4ed0-ffffffff815e4f4a: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81693f40)
Location: block/ioprio.c:33
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/io_uring.c:io_prep_rw
```
**Symbols:**

```
ffffffff81693f40-ffffffff81693fb6: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81752f10)
Location: block/ioprio.c:33
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/rw.c:io_prep_rw
```
**Symbols:**

```
ffffffff81752f10-ffffffff81752f86: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8178f0e0)
Location: block/ioprio.c:33
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/rw.c:io_prep_rw
```
**Symbols:**

```
ffffffff8178f0e0-ffffffff8178f15d: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff817d19c0)
Location: block/ioprio.c:33
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/rw.c:io_prep_rw
```
**Symbols:**

```
ffffffff817d19c0-ffffffff817d1a3d: ioprio_check_cap (STB_GLOBAL)
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
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffff8000105fe0c8)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__arm64_sys_ioprio_set
```
**Symbols:**

```
ffff8000105fe0c8-ffff8000105fe150: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (c07a8ca8)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
c07a8ca8-c07a8d1c: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (c000000000797cc0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
c000000000797cc0-c000000000797d80: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffe0004397d0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
ffffffe0004397d0-ffffffe000439836: ioprio_check_cap (STB_GLOBAL)
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
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814f4940)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814f4940-ffffffff814f49a1: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814e4e50)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814e4e50-ffffffff814e4eb1: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814f09d0)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814f09d0-ffffffff814f0a31: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81509a70)
Location: block/ioprio.c:65
Inline: False
Direct callers:
  - fs/aio.c:aio_prep_rw
  - fs/io_uring.c:io_prep_rw
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff81509a70-ffffffff81509ad1: ioprio_check_cap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
