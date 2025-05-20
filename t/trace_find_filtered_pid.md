# Function: <code>trace_find_filtered_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811566f0)
Location: kernel/trace/trace.c:336
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811566f0-ffffffff8115670a: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161800)
Location: kernel/trace/trace.c:338
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff81161800-ffffffff8116181a: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81164b80)
Location: kernel/trace/trace.c:330
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff81164b80-ffffffff81164b9a: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81171b26)
Location: kernel/trace/trace.c:330
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8116fda0-ffffffff8116fdb4: trace_find_filtered_pid.part.56 (STB_LOCAL)
ffffffff81171ac0-ffffffff81171ad2: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81180c76)
Location: kernel/trace/trace.c:331
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8117ec80-ffffffff8117ec94: trace_find_filtered_pid.part.53 (STB_LOCAL)
ffffffff81180c10-ffffffff81180c22: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118e636)
Location: kernel/trace/trace.c:332
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8118c580-ffffffff8118c594: trace_find_filtered_pid.part.54 (STB_LOCAL)
ffffffff8118e5d0-ffffffff8118e5e2: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c05f)
Location: kernel/trace/trace.c:334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff81199c90-ffffffff81199c9f: trace_find_filtered_pid.part.0 (STB_LOCAL)
ffffffff8119bff0-ffffffff8119c002: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a7a4f)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811a5640-ffffffff811a564f: trace_find_filtered_pid.part.0 (STB_LOCAL)
ffffffff811a79e0-ffffffff811a79f2: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfdc3)
Location: kernel/trace/trace.c:367
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811bfd40-ffffffff811bfd56: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd9f3)
Location: kernel/trace/trace.c:518
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811bd970-ffffffff811bd986: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd4f3)
Location: kernel/trace/trace.c:520
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811bd470-ffffffff811bd486: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e7fe3)
Location: kernel/trace/trace.c:533
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811e7f60-ffffffff811e7f76: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121fa57)
Location: kernel/trace/trace.c:537
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8121f9c0-ffffffff8121f9d3: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126a657)
Location: kernel/trace/trace.c:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8126a5a0-ffffffff8126a5b3: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812817d7)
Location: kernel/trace/trace.c:577
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff81281720-ffffffff81281733: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129c687)
Location: kernel/trace/trace.c:579
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8129c5d0-ffffffff8129c5e3: trace_find_filtered_pid (STB_GLOBAL)
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
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010223fc8)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffff800010223f28-ffff800010223f64: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c046174c)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
c0461688-c04616d0: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a8db8)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
c0000000002a8cf0-c0000000002a8d38: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017f544)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffe00017f4b8-ffffffe00017f4f0: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a006f)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8119dc60-ffffffff8119dc6f: trace_find_filtered_pid.part.0 (STB_LOCAL)
ffffffff811a0000-ffffffff811a0012: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119307f)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff81190cc0-ffffffff81190ccf: trace_find_filtered_pid.part.0 (STB_LOCAL)
ffffffff81193010-ffffffff81193022: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119de3f)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8119ba30-ffffffff8119ba3f: trace_find_filtered_pid.part.0 (STB_LOCAL)
ffffffff8119ddd0-ffffffff8119dde2: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list *filtered_pids, pid_t search_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811abb1f)
Location: kernel/trace/trace.c:352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff811a96d0-ffffffff811a96df: trace_find_filtered_pid.part.0 (STB_LOCAL)
ffffffff811abab0-ffffffff811abac2: trace_find_filtered_pid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
