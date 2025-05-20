# Function: <code>__bpf_trace_mem_disconnect</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa, bool safe_to_remove, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811cfbe0)
Location: include/trace/events/xdp.h:317
Inline: False
```
**Symbols:**

```
ffffffff811cfbe0-ffffffff811cfbf1: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dc240)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
ffffffff811dc240-ffffffff811dc24b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8df0)
Location: include/trace/events/xdp.h:300
Inline: False
```
**Symbols:**

```
ffffffff811f8df0-ffffffff811f8dfb: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7e30)
Location: include/trace/events/xdp.h:308
Inline: False
```
**Symbols:**

```
ffffffff811f7e30-ffffffff811f7e3b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8c10)
Location: include/trace/events/xdp.h:316
Inline: False
```
**Symbols:**

```
ffffffff811f8c10-ffffffff811f8c1b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122a200)
Location: include/trace/events/xdp.h:320
Inline: False
```
**Symbols:**

```
ffffffff8122a200-ffffffff8122a20b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126bc40)
Location: include/trace/events/xdp.h:320
Inline: False
```
**Symbols:**

```
ffffffff8126bc40-ffffffff8126bc53: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c0e70)
Location: include/trace/events/xdp.h:320
Inline: False
```
**Symbols:**

```
ffffffff812c0e70-ffffffff812c0e83: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e7c20)
Location: include/trace/events/xdp.h:320
Inline: False
```
**Symbols:**

```
ffffffff812e7c20-ffffffff812e7c33: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81305f10)
Location: include/trace/events/xdp.h:321
Inline: True
```
**Symbols:**

```
ffffffff81305f10-ffffffff81305f23: __bpf_trace_mem_disconnect (STB_LOCAL)
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
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025c2e8)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
ffff80001025c2e8-ffff80001025c2fc: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04902b0)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
c04902b0-c04902cc: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003012a0)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
c0000000003012a0-c0000000003012cc: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4860)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
ffffffff811d4860-ffffffff811d486b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c7620)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
ffffffff811c7620-ffffffff811c762b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d2630)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
ffffffff811d2630-ffffffff811d263b: __bpf_trace_mem_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mem_disconnect(void *__data, const struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e0920)
Location: include/trace/events/xdp.h:318
Inline: False
```
**Symbols:**

```
ffffffff811e0920-ffffffff811e092b: __bpf_trace_mem_disconnect (STB_LOCAL)
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
<b>Param removed. </b>
<code>bool safe_to_remove</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force</code>
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
