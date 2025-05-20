# Function: <code>__bpf_trace_clk_rate_range</code>

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
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81718e00)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff81718e00-ffffffff81718e0b: __bpf_trace_clk_rate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fa0f0)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff816fa0f0-ffffffff816fa0fb: __bpf_trace_clk_rate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81774850)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff81774850-ffffffff8177485b: __bpf_trace_clk_rate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aa630)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff818aa630-ffffffff818aa647: __bpf_trace_clk_rate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f5880)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff819f5880-ffffffff819f5897: __bpf_trace_clk_rate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3e000)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff81a3e000-ffffffff81a3e017: __bpf_trace_clk_rate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_clk_rate_range(void *__data, struct clk_core *core, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a898f0)
Location: include/trace/events/clk.h:135
Inline: False
```
**Symbols:**

```
ffffffff81a898f0-ffffffff81a89907: __bpf_trace_clk_rate_range (STB_LOCAL)
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
