# Function: <code>stack_trace_snprint</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff811261cd-ffffffff811261e3: stack_trace_snprint.cold (STB_LOCAL)
ffffffff81125de0-ffffffff81125e85: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81131db0)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff81131db0-ffffffff81131e4e: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811411d0)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff811411d0-ffffffff81141273: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d470)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff8113d470-ffffffff8113d513: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e6c0)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff8113e6c0-ffffffff8113e763: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161b50)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff81161b50-ffffffff81161bf3: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194a30)
Location: kernel/stacktrace.c:47
Inline: True
Direct callers:
  - lib/stackdepot.c:stack_depot_snprint
```
**Symbols:**

```
ffffffff81194a30-ffffffff81194ae3: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d26f0)
Location: kernel/stacktrace.c:47
Inline: True
Direct callers:
  - lib/stackdepot.c:stack_depot_snprint
```
**Symbols:**

```
ffffffff811d26f0-ffffffff811d27a3: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e69e0)
Location: kernel/stacktrace.c:47
Inline: True
Direct callers:
  - lib/stackdepot.c:stack_depot_snprint
```
**Symbols:**

```
ffffffff811e69e0-ffffffff811e6a93: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc730)
Location: kernel/stacktrace.c:47
Inline: True
Direct callers:
  - lib/stackdepot.c:stack_depot_snprint
```
**Symbols:**

```
ffffffff811fc730-ffffffff811fc7e3: stack_trace_snprint (STB_GLOBAL)
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
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffff8000101998a8)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffff8000101998a8-ffff800010199984: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c03e42a8)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
c03e42a8-c03e439c: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c0000000001f9ac0)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
c0000000001f9ac0-c0000000001f9be0: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffe000129e88)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffe000129e88-ffffffe000129f28: stack_trace_snprint (STB_GLOBAL)
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
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a560)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff8112a560-ffffffff8112a5fe: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111cdd0)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff8111cdd0-ffffffff8111ce6e: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81128280)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff81128280-ffffffff8112831e: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int stack_trace_snprint(char *buf, size_t size, const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81134910)
Location: kernel/stacktrace.c:46
Inline: True
```
**Symbols:**

```
ffffffff81134910-ffffffff811349ae: stack_trace_snprint (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int *entries</code> ➡️ <code>const long unsigned int *entries</code>
</li>
</ul>
</details>
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
