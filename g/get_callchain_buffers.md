# Function: <code>get_callchain_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_callchain_buffers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81186070)
Location: kernel/events/callchain.c:97
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81186070-ffffffff811861da: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81198320)
Location: kernel/events/callchain.c:107
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81198320-ffffffff811984d8: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811a7d00)
Location: kernel/events/callchain.c:107
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811a7d00-ffffffff811a7ebc: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811af490)
Location: kernel/events/callchain.c:109
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811af490-ffffffff811af606: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811c3040)
Location: kernel/events/callchain.c:109
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811c3040-ffffffff811c319e: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811e33e0)
Location: kernel/events/callchain.c:109
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811e33e0-ffffffff811e3538: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811f38a0)
Location: kernel/events/callchain.c:109
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811f38a0-ffffffff811f39f8: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8120b670)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8120b670-ffffffff8120b6e9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81218950)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81218950-ffffffff812189c9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81244690)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81244690-ffffffff81244709: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8124ec60)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8124ec60-ffffffff8124ecd9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81253570)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81253570-ffffffff812535e9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8128eeb0)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8128eeb0-ffffffff8128ef29: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff812e3dd0)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff812e3dd0-ffffffff812e3e49: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8134c4e0)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8134c4e0-ffffffff8134c559: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8137d530)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8137d530-ffffffff8137d5a9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff813a6790)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff813a6790-ffffffff813a6809: get_callchain_buffers (STB_GLOBAL)
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
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffff8000102a3538)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffff8000102a3538-ffff8000102a3774: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (c04d2dc8)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
c04d2dc8-c04d2f88: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (c000000000355a60)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
c000000000355a60-c000000000355b8c: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffe0001d1c3c)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffe0001d1c3c-ffffffe0001d1daa: get_callchain_buffers (STB_GLOBAL)
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
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81210fa0)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81210fa0-ffffffff81211019: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81203d30)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81203d30-ffffffff81203da9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8120ed40)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8120ed40-ffffffff8120edb9: get_callchain_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8121dc50)
Location: kernel/events/callchain.c:108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8121dc50-ffffffff8121dcc9: get_callchain_buffers (STB_GLOBAL)
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
<b>Param added. </b>
<code>int event_max_stack</code>
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
