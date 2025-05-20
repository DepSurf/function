# Function: <code>do_madvise</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_madvise(long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff812b66e9)
Location: mm/madvise.c:1054
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff812b6250-ffffffff812b667d: do_madvise.part.0 (STB_LOCAL)
ffffffff812b7a60-ffffffff812b7aa0: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff812c1aae)
Location: mm/madvise.c:1058
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff812c11b0-ffffffff812c1856: do_madvise.part.0 (STB_LOCAL)
ffffffff81be865a-ffffffff81be86c8: do_madvise.part.0.cold (STB_LOCAL)
ffffffff812c3190-ffffffff812c31d2: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff812c89a3)
Location: mm/madvise.c:1059
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff812c7fc0-ffffffff812c8758: do_madvise.part.0 (STB_LOCAL)
ffffffff81bda546-ffffffff81bda5b4: do_madvise.part.0.cold (STB_LOCAL)
ffffffff812c9ff0-ffffffff812ca032: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff8130d926)
Location: mm/madvise.c:1128
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8130cd90-ffffffff8130d728: do_madvise.part.0 (STB_LOCAL)
ffffffff81cbe770-ffffffff81cbe84f: do_madvise.part.0.cold (STB_LOCAL)
ffffffff8130f010-ffffffff8130f052: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813789b0)
Location: mm/madvise.c:1368
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - io_uring/io_uring.c:io_madvise
```
**Symbols:**

```
ffffffff813789b0-ffffffff81378c02: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f62e0)
Location: mm/madvise.c:1402
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - io_uring/advise.c:io_madvise
```
**Symbols:**

```
ffffffff813f62e0-ffffffff813f6532: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1404
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - io_uring/advise.c:io_madvise
```
**Symbols:**

```
ffffffff820e50c9-ffffffff820e50e2: do_madvise.cold (STB_LOCAL)
ffffffff814290d0-ffffffff8142945a: do_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_madvise(struct mm_struct *mm, long unsigned int start, size_t len_in, int behavior);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1398
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - io_uring/advise.c:io_madvise
```
**Symbols:**

```
ffffffff821c22a6-ffffffff821c22be: do_madvise.cold (STB_LOCAL)
ffffffff81462900-ffffffff81462c8a: do_madvise (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, len_in, behavior</code> ➡️ <code>mm, start, len_in, behavior</code>
</li>
</ul>
</details>
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
