# Function: <code>build_open_flags</code>

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
In fs/open.c (ffffffff8120a55c)
Location: fs/open.c:892
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
  - fs/open.c:do_sys_open
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
In fs/open.c (ffffffff812313fe)
Location: fs/open.c:888
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812439ae)
Location: fs/open.c:905
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff8124f14e)
Location: fs/open.c:905
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812710ce)
Location: fs/open.c:905
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff81296d2e)
Location: fs/open.c:947
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812ab9ce)
Location: fs/open.c:934
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812c81d0)
Location: fs/open.c:954
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812d9be0)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e96a)
Location: fs/open.c:1006
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff8130f820-ffffffff8130f9aa: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131ac3a)
Location: fs/open.c:995
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff8131bad0-ffffffff8131bc6b: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81320a22)
Location: fs/open.c:1003
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff81321c20-ffffffff81321dd1: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e2b0)
Location: fs/open.c:1021
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff8136f100-ffffffff8136f2b1: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813edae0)
Location: fs/open.c:1086
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - io_uring/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff813edae0-ffffffff813edcc4: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81476250)
Location: fs/open.c:1118
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff81476250-ffffffff81476434: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a94f1)
Location: fs/open.c:1207
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814aab80-ffffffff814aad75: build_open_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int build_open_flags(const struct open_how *how, struct open_flags *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814da551)
Location: fs/open.c:1204
Inline: True
Inline callers:
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
Direct callers:
  - fs/open.c:do_sys_openat2
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814dc020-ffffffff814dc215: build_open_flags (STB_GLOBAL)
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
In fs/open.c (ffff80001037ef90)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c056986c)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (c000000000474dc0)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffe000254b5c)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812d21c0)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812c2e40)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812cffd0)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
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
In fs/open.c (ffffffff812e0de0)
Location: fs/open.c:959
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:file_open_root
  - fs/open.c:file_open_name
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
