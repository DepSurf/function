# Function: <code>peek_next_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114aef0)
Location: kernel/trace/trace.c:2285
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8114aef0-ffffffff8114af5f: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81153a30)
Location: kernel/trace/trace.c:2622
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81153a30-ffffffff81153a9f: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115dca0)
Location: kernel/trace/trace.c:2846
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8115dca0-ffffffff8115dd0f: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160e10)
Location: kernel/trace/trace.c:3058
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81160e10-ffffffff81160e7f: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116dee0)
Location: kernel/trace/trace.c:3067
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8116dee0-ffffffff8116df4f: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117ce90)
Location: kernel/trace/trace.c:3073
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8117ce90-ffffffff8117cf00: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118a6f0)
Location: kernel/trace/trace.c:3075
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8118a6f0-ffffffff8118a76c: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197de0)
Location: kernel/trace/trace.c:3250
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81197de0-ffffffff81197e57: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3780)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811a3780-ffffffff811a37f7: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9d00)
Location: kernel/trace/trace.c:3395
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811b9d00-ffffffff811b9da3: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b78d0)
Location: kernel/trace/trace.c:3463
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811b78d0-ffffffff811b7973: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b8420)
Location: kernel/trace/trace.c:3512
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811b8420-ffffffff811b84c3: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e28f0)
Location: kernel/trace/trace.c:3572
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811e28f0-ffffffff811e2993: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81219820)
Location: kernel/trace/trace.c:3570
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81219820-ffffffff812198e0: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812636e0)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff812636e0-ffffffff812637a0: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127a840)
Location: kernel/trace/trace.c:3688
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8127a840-ffffffff8127a900: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812953d0)
Location: kernel/trace/trace.c:3665
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff812953d0-ffffffff81295490: peek_next_entry (STB_LOCAL)
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
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021e950)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffff80001021e950-ffff80001021e9d0: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045c8f4)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
c045c8f4-c045c974: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a1ef0)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
c0000000002a1ef0-c0000000002a1fd0: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017b37a)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffe00017b37a-ffffffe00017b3fa: peek_next_entry (STB_LOCAL)
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
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119bda0)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8119bda0-ffffffff8119be17: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ee20)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8118ee20-ffffffff8118ee97: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199b70)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81199b70-ffffffff81199be7: peek_next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct trace_entry *peek_next_entry(struct trace_iterator *iter, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a7810)
Location: kernel/trace/trace.c:3276
Inline: False
Direct callers:
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811a7810-ffffffff811a7887: peek_next_entry (STB_LOCAL)
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
