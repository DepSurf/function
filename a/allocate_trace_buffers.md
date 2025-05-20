# Function: <code>allocate_trace_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114cb70)
Location: kernel/trace/trace.c:6549
Inline: True
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:trace_init
```
**Symbols:**

```
ffffffff8114cb70-ffffffff8114cbf8: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811554d0)
Location: kernel/trace/trace.c:6949
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811554d0-ffffffff81155550: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115f910)
Location: kernel/trace/trace.c:7232
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8115f910-ffffffff8115f990: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162d00)
Location: kernel/trace/trace.c:7596
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81162d00-ffffffff81162d71: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116fc90)
Location: kernel/trace/trace.c:7600
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8116fc90-ffffffff8116fd11: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117eb70)
Location: kernel/trace/trace.c:7690
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8117eb70-ffffffff8117ebf1: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118c470)
Location: kernel/trace/trace.c:7759
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8118c470-ffffffff8118c4f1: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199a4d)
Location: kernel/trace/trace.c:8244
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81199a30-ffffffff81199a8a: allocate_trace_buffers (STB_LOCAL)
ffffffff811a1a26-ffffffff811a1a60: allocate_trace_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a53b0)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a53b0-ffffffff811a5431: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc68d)
Location: kernel/trace/trace.c:8498
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811bc670-ffffffff811bc6fc: allocate_trace_buffers (STB_LOCAL)
ffffffff811c519c-ffffffff811c51b4: allocate_trace_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba29d)
Location: kernel/trace/trace.c:8572
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811ba280-ffffffff811ba30c: allocate_trace_buffers (STB_LOCAL)
ffffffff81be54d8-ffffffff81be54f0: allocate_trace_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba70d)
Location: kernel/trace/trace.c:8908
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811ba6f0-ffffffff811ba77c: allocate_trace_buffers (STB_LOCAL)
ffffffff81bd7386-ffffffff81bd739e: allocate_trace_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e722b)
Location: kernel/trace/trace.c:9072
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811e4ed0-ffffffff811e4f85: allocate_trace_buffers.part.0 (STB_LOCAL)
ffffffff81cb4d84-ffffffff81cb4de7: allocate_trace_buffers.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f1af)
Location: kernel/trace/trace.c:9104
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8121c3b0-ffffffff8121c479: allocate_trace_buffers.part.0 (STB_LOCAL)
ffffffff81e65daa-ffffffff81e65e0d: allocate_trace_buffers.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9208
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81265fb0-ffffffff81266097: allocate_trace_buffers (STB_LOCAL)
ffffffff8205d34a-ffffffff8205d38f: allocate_trace_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9371
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8127cb50-ffffffff8127cc37: allocate_trace_buffers (STB_LOCAL)
ffffffff820dbcd9-ffffffff820dbd1e: allocate_trace_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9550
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_systems
```
**Symbols:**

```
ffffffff812978e0-ffffffff812979c7: allocate_trace_buffers (STB_LOCAL)
ffffffff821b7b34-ffffffff821b7b79: allocate_trace_buffers.cold (STB_LOCAL)
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
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010220558)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffff800010220558-ffff8000102205e4: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045e3fc)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c045e3fc-c045e49c: allocate_trace_buffers (STB_LOCAL)
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
In kernel/trace/trace.c (c000000001373f28)
Location: kernel/trace/trace.c:8295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c0000000002a44d0-c0000000002a4590: allocate_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ceae)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffe00017ceae-ffffffe00017cf34: allocate_trace_buffers (STB_LOCAL)
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
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d9d0)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8119d9d0-ffffffff8119da51: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190a30)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81190a30-ffffffff81190ab1: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b7a0)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8119b7a0-ffffffff8119b821: allocate_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int allocate_trace_buffers(struct trace_array *tr, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9440)
Location: kernel/trace/trace.c:8295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a9440-ffffffff811a94c1: allocate_trace_buffers (STB_LOCAL)
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
