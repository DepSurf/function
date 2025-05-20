# Function: <code>ftrace_location_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140530)
Location: kernel/trace/ftrace.c:1565
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff81140530-ffffffff811405d2: ftrace_location_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114aae0)
Location: kernel/trace/ftrace.c:1546
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff8114aae0-ffffffff8114ab82: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811549d0)
Location: kernel/trace/ftrace.c:1552
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff811549d0-ffffffff81154a72: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157340)
Location: kernel/trace/ftrace.c:1637
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff81157340-ffffffff811573e0: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81163eb0)
Location: kernel/trace/ftrace.c:1613
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff81163eb0-ffffffff81163f50: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81172d20)
Location: kernel/trace/ftrace.c:1602
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff81172d20-ffffffff81172dc0: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81180940)
Location: kernel/trace/ftrace.c:1551
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff81180940-ffffffff811809e0: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d9d0)
Location: kernel/trace/ftrace.c:1548
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffff8118d9d0-ffffffff8118da70: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81199640)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff81199640-ffffffff811996e0: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1661)
Location: kernel/trace/ftrace.c:1564
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff811af570-ffffffff811af589: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af0d1)
Location: kernel/trace/ftrace.c:1563
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff811acf20-ffffffff811acf39: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af931)
Location: kernel/trace/ftrace.c:1563
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff811ad9c0-ffffffff811ad9d9: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d97a1)
Location: kernel/trace/ftrace.c:1564
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff811d7740-ffffffff811d7759: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120cde0)
Location: kernel/trace/ftrace.c:1558
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff8120cc60-ffffffff8120cc82: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81255940)
Location: kernel/trace/ftrace.c:1564
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff81255790-ffffffff812557b2: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126ccc0)
Location: kernel/trace/ftrace.c:1596
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff8126cb10-ffffffff8126cb32: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812872b0)
Location: kernel/trace/ftrace.c:1595
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_text_reserved
Direct callers:
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff81287100-ffffffff81287122: ftrace_location_range (STB_GLOBAL)
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
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102121a8)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffff8000102121a8-ffff800010212280: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0450cc8)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
c0450cc8-c0450d94: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000291fd0)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_lookup_name
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
c000000000291fd0-c0000000002920f8: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001725ca)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
```
**Symbols:**

```
ffffffe0001725ca-ffffffe00017264c: ftrace_location_range (STB_GLOBAL)
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
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191c60)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff81191c60-ffffffff81191d00: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184d70)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff81184d70-ffffffff81184e10: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118fa30)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff8118fa30-ffffffff8118fad0: ftrace_location_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int ftrace_location_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d5e0)
Location: kernel/trace/ftrace.c:1549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_text_reserved
  - kernel/trace/trace_kprobe.c:__within_notrace_func
```
**Symbols:**

```
ffffffff8119d5e0-ffffffff8119d680: ftrace_location_range (STB_GLOBAL)
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
