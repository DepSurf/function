# Function: <code>get_perf_callchain</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81198530)
Location: kernel/events/callchain.c:195
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/callchain.c:perf_callchain
```
**Symbols:**

```
ffffffff81198530-ffffffff81198753: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811a7f10)
Location: kernel/events/callchain.c:195
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/callchain.c:perf_callchain
```
**Symbols:**

```
ffffffff811a7f10-ffffffff811a8133: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811af660)
Location: kernel/events/callchain.c:197
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/callchain.c:perf_callchain
```
**Symbols:**

```
ffffffff811af660-ffffffff811af8f7: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811c31f0)
Location: kernel/events/callchain.c:197
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/callchain.c:perf_callchain
```
**Symbols:**

```
ffffffff811c31f0-ffffffff811c349d: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811e3590)
Location: kernel/events/callchain.c:179
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff811e3590-ffffffff811e37fe: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811f3a50)
Location: kernel/events/callchain.c:179
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff811f3a50-ffffffff811f3ccc: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8120b740)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8120b740-ffffffff8120b9b0: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81218a20)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff81218a20-ffffffff81218c90: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81244760)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff81244760-ffffffff8124496b: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8124ee20)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8124ee20-ffffffff8124efbc: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81253730)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff81253730-ffffffff812538cc: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8128f070)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8128f070-ffffffff8128f20c: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff812e3fd0)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff812e3fd0-ffffffff812e419d: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8134c720)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8134c720-ffffffff8134c8ed: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8137d770)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8137d770-ffffffff8137d93e: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff813a69d0)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff813a69d0-ffffffff813a6b9e: get_perf_callchain (STB_GLOBAL)
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
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffff8000102a37e0)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffff8000102a37e0-ffff8000102a3ae8: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (c04d2fe4)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
c04d2fe4-c04d32cc: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (c000000000355c30)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
c000000000355c30-c000000000355f8c: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffe0001d1e16)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffe0001d1e16-ffffffe0001d2024: get_perf_callchain (STB_GLOBAL)
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
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81211070)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff81211070-ffffffff812112e0: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81203e00)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff81203e00-ffffffff81204070: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8120ee10)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8120ee10-ffffffff8120f080: get_perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct perf_callchain_entry *get_perf_callchain(struct pt_regs *regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8121dd20)
Location: kernel/events/callchain.c:178
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/events/core.c:perf_callchain
```
**Symbols:**

```
ffffffff8121dd20-ffffffff8121df90: get_perf_callchain (STB_GLOBAL)
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
