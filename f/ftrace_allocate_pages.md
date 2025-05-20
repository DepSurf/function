# Function: <code>ftrace_allocate_pages</code>

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
In kernel/trace/ftrace.c (ffffffff811432d6)
Location: kernel/trace/ftrace.c:2947
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff8114b178)
Location: kernel/trace/ftrace.c:2967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff81155068)
Location: kernel/trace/ftrace.c:2985
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff811579c8)
Location: kernel/trace/ftrace.c:3083
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff811644c8)
Location: kernel/trace/ftrace.c:3051
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff81173235)
Location: kernel/trace/ftrace.c:3040
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff81180e55)
Location: kernel/trace/ftrace.c:2999
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff8118dc77)
Location: kernel/trace/ftrace.c:2997
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff81199bd7)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3115
Inline: False
```
**Symbols:**

```
ffffffff811ad6a0-ffffffff811ad85f: ftrace_allocate_pages (STB_LOCAL)
ffffffff811b4670-ffffffff811b4689: ftrace_allocate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3193
Inline: False
```
**Symbols:**

```
ffffffff811aafb0-ffffffff811ab16f: ftrace_allocate_pages (STB_LOCAL)
ffffffff81be512d-ffffffff81be5146: ftrace_allocate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3193
Inline: False
```
**Symbols:**

```
ffffffff811aba70-ffffffff811abbdc: ftrace_allocate_pages (STB_LOCAL)
ffffffff81bd6f70-ffffffff81bd6f89: ftrace_allocate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3194
Inline: False
```
**Symbols:**

```
ffffffff811d5690-ffffffff811d5814: ftrace_allocate_pages (STB_LOCAL)
ffffffff81cb424b-ffffffff81cb42d0: ftrace_allocate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3206
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
**Symbols:**

```
ffffffff8120a7f0-ffffffff8120a974: ftrace_allocate_pages (STB_LOCAL)
ffffffff81e6521e-ffffffff81e652a1: ftrace_allocate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3226
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
**Symbols:**

```
ffffffff812530d0-ffffffff81253257: ftrace_allocate_pages (STB_LOCAL)
ffffffff8205cc07-ffffffff8205cc79: ftrace_allocate_pages.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8126d52d)
Location: kernel/trace/ftrace.c:3325
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ftrace_page *ftrace_allocate_pages(long unsigned int num_to_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:3291
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
**Symbols:**

```
ffffffff81284aa0-ffffffff81284c41: ftrace_allocate_pages (STB_LOCAL)
ffffffff821b72b0-ffffffff821b731e: ftrace_allocate_pages.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffff800010212804)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (c0451428)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (c000000000292508)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffe000172bda)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff811921f7)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff81185303)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff8118ffc7)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff8119db77)
Location: kernel/trace/ftrace.c:2998
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
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
</ul>
