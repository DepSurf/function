# Function: <code>tracer_alloc_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81f83e59)
Location: kernel/trace/trace.c:7197
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81fad3eb)
Location: kernel/trace/trace.c:7605
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81fe9711)
Location: kernel/trace/trace.c:7891
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff820ca0f1)
Location: kernel/trace/trace.c:8263
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826d27c0)
Location: kernel/trace/trace.c:8360
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826fcfa9)
Location: kernel/trace/trace.c:8465
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b3ec3)
Location: kernel/trace/trace.c:8539
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828cca29)
Location: kernel/trace/trace.c:9044
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff828cca29-ffffffff828ccd79: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d4f47)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff828d4f47-ffffffff828d52b3: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff82cf58c0)
Location: kernel/trace/trace.c:9386
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff82cf58c0-ffffffff82cf5c08: tracer_alloc_buffers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff82fe24a5)
Location: kernel/trace/trace.c:9519
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff82fe24a5-ffffffff82fe27e6: tracer_alloc_buffers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff831ec976)
Location: kernel/trace/trace.c:9841
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff831ec976-ffffffff831ecce6: tracer_alloc_buffers.isra.0 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff832d1498)
Location: kernel/trace/trace.c:10003
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff832d1498-ffffffff832d1865: tracer_alloc_buffers.isra.0 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff834856d5)
Location: kernel/trace/trace.c:10049
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff834856d5-ffffffff83485aac: tracer_alloc_buffers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb4690)
Location: kernel/trace/trace.c:10144
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff83eb4690-ffffffff83eb4af5: tracer_alloc_buffers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d99a0)
Location: kernel/trace/trace.c:10382
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff836d99a0-ffffffff836d9e1a: tracer_alloc_buffers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390bf50)
Location: kernel/trace/trace.c:10577
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff8390bf50-ffffffff8390c374: tracer_alloc_buffers.isra.0 (STB_LOCAL)
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
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001144d808)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffff80001144d808-ffff80001144dab8: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c1527da0)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
c1527da0-c1528090: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c000000001373da8)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
c000000001373da8-c000000001374138: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00000de20)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffe00000de20-ffffffe00000e136: tracer_alloc_buffers (STB_LOCAL)
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
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828bddf8)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff828bddf8-ffffffff828be164: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b6498)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff828b6498-ffffffff828b6804: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d0b7b)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff828d0b7b-ffffffff828d0ee7: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tracer_alloc_buffers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d5f9c)
Location: kernel/trace/trace.c:9100
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff828d5f9c-ffffffff828d6308: tracer_alloc_buffers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
