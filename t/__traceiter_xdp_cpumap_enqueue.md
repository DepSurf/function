# Function: <code>__traceiter_xdp_cpumap_enqueue</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f6630)
Location: include/trace/events/xdp.h:220
Inline: False
```
**Symbols:**

```
ffffffff811f6630-ffffffff811f668b: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7550)
Location: include/trace/events/xdp.h:228
Inline: False
```
**Symbols:**

```
ffffffff811f7550-ffffffff811f75a9: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81228b20)
Location: include/trace/events/xdp.h:232
Inline: False
```
**Symbols:**

```
ffffffff81228b20-ffffffff81228b79: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81269b40)
Location: include/trace/events/xdp.h:232
Inline: False
```
**Symbols:**

```
ffffffff81269b40-ffffffff81269ba8: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812beae0)
Location: include/trace/events/xdp.h:232
Inline: False
```
**Symbols:**

```
ffffffff812beae0-ffffffff812beb48: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e57a0)
Location: include/trace/events/xdp.h:232
Inline: False
```
**Symbols:**

```
ffffffff812e57a0-ffffffff812e5808: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_xdp_cpumap_enqueue(void *__data, int map_id, unsigned int processed, unsigned int drops, int to_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81303850)
Location: include/trace/events/xdp.h:233
Inline: False
```
**Symbols:**

```
ffffffff81303850-ffffffff813038b8: __traceiter_xdp_cpumap_enqueue (STB_GLOBAL)
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
