# Function: <code>rb_allocate_cpu_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81149ce0)
Location: kernel/trace/ring_buffer.c:1205
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_cpu_notify
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81149ce0-ffffffff81149fc2: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811506f0)
Location: kernel/trace/ring_buffer.c:1196
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_cpu_notify
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811506f0-ffffffff811509cc: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115b850)
Location: kernel/trace/ring_buffer.c:1194
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8115b850-ffffffff8115bb26: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115e790)
Location: kernel/trace/ring_buffer.c:1196
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8115e790-ffffffff8115ea23: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116b790)
Location: kernel/trace/ring_buffer.c:1199
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8116b790-ffffffff8116ba23: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117ac00)
Location: kernel/trace/ring_buffer.c:1260
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8117ac00-ffffffff8117aea0: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81187670)
Location: kernel/trace/ring_buffer.c:1308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81187670-ffffffff81187910: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:1285
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81194b90-ffffffff81194e44: rb_allocate_cpu_buffer (STB_LOCAL)
ffffffff8119711d-ffffffff81197134: rb_allocate_cpu_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0650)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811a0650-ffffffff811a090b: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6c30)
Location: kernel/trace/ring_buffer.c:1288
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811b6c30-ffffffff811b6eeb: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b47d0)
Location: kernel/trace/ring_buffer.c:1535
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811b47d0-ffffffff811b4aa1: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3b90)
Location: kernel/trace/ring_buffer.c:1618
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811b3b90-ffffffff811b3e61: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811ddb40)
Location: kernel/trace/ring_buffer.c:1618
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811ddb40-ffffffff811dde71: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81214c90)
Location: kernel/trace/ring_buffer.c:1654
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81214c90-ffffffff81214fb7: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125e350)
Location: kernel/trace/ring_buffer.c:1716
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8125e350-ffffffff8125e67c: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81275530)
Location: kernel/trace/ring_buffer.c:1710
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81275530-ffffffff8127585c: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct trace_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128fbe0)
Location: kernel/trace/ring_buffer.c:1541
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8128fbe0-ffffffff8128ff1f: rb_allocate_cpu_buffer (STB_LOCAL)
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
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010219e70)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffff800010219e70-ffff80001021a0e8: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0457384)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
c0457384-c04575b0: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029bf30)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
c00000000029bf30-c00000000029c258: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177c2a)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffe000177c2a-ffffffe000177e02: rb_allocate_cpu_buffer (STB_LOCAL)
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
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198c70)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81198c70-ffffffff81198f2b: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118c4b0)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff8118c4b0-ffffffff8118c76b: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196a40)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff81196a40-ffffffff81196cfb: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_per_cpu *rb_allocate_cpu_buffer(struct ring_buffer *buffer, long int nr_pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4650)
Location: kernel/trace/ring_buffer.c:1286
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
**Symbols:**

```
ffffffff811a4650-ffffffff811a490b: rb_allocate_cpu_buffer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_pages</code> ➡️ <code>long int nr_pages</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
</li>
</ul>
</details>
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
