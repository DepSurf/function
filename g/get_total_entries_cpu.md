# Function: <code>get_total_entries_cpu</code>

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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199880)
Location: kernel/trace/trace.c:3494
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff81199880-ffffffff811998f9: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5180)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff811a5180-ffffffff811a51f9: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c25fd)
Location: kernel/trace/trace.c:3684
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff811b9f30-ffffffff811b9fa8: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c020d)
Location: kernel/trace/trace.c:3752
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff811b7b00-ffffffff811b7b78: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0f0d)
Location: kernel/trace/trace.c:4079
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff811b8650-ffffffff811b86ba: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811eb9e5)
Location: kernel/trace/trace.c:4151
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff811e2b20-ffffffff811e2bde: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81223a85)
Location: kernel/trace/trace.c:4154
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff81219a60-ffffffff81219b2c: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126eb75)
Location: kernel/trace/trace.c:4178
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff812637b0-ffffffff8126387c: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81285dd5)
Location: kernel/trace/trace.c:4279
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff8127a910-ffffffff8127a9dc: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void get_total_entries_cpu(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a0ee5)
Location: kernel/trace/trace.c:4241
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
Direct callers:
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff812954a0-ffffffff8129556c: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffff8000102202c8)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffff8000102202c8-ffff800010220368: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void get_total_entries_cpu(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045cb28)
Location: kernel/trace/trace.c:3520
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
c045cb28-c045cba0: get_total_entries_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c0000000002a4140)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
c0000000002a4140-c0000000002a4230: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ccae)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffe00017ccae-ffffffe00017cd24: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d7a0)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff8119d7a0-ffffffff8119d819: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190800)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff81190800-ffffffff81190879: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b570)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff8119b570-ffffffff8119b5e9: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9210)
Location: kernel/trace/trace.c:3520
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_total_entries_cpu
  - kernel/trace/trace.c:get_total_entries
```
**Symbols:**

```
ffffffff811a9210-ffffffff811a9289: get_total_entries_cpu.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
