# Function: <code>hwlat_tracer_stop</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8116d0f0)
Location: kernel/trace/trace_hwlat.c:568
Inline: False
```
**Symbols:**

```
ffffffff8116d0f0-ffffffff8116d113: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811703e0)
Location: kernel/trace/trace_hwlat.c:566
Inline: False
```
**Symbols:**

```
ffffffff811703e0-ffffffff81170404: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8117d5c0)
Location: kernel/trace/trace_hwlat.c:566
Inline: False
```
**Symbols:**

```
ffffffff8117d5c0-ffffffff8117d5e4: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8118c6d0)
Location: kernel/trace/trace_hwlat.c:566
Inline: False
```
**Symbols:**

```
ffffffff8118c6d0-ffffffff8118c6f3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8119a040)
Location: kernel/trace/trace_hwlat.c:567
Inline: False
```
**Symbols:**

```
ffffffff8119a040-ffffffff8119a063: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811a7ca0)
Location: kernel/trace/trace_hwlat.c:567
Inline: False
```
**Symbols:**

```
ffffffff811a7ca0-ffffffff811a7cc3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811b34a0)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffffffff811b34a0-ffffffff811b34c3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811cc330)
Location: kernel/trace/trace_hwlat.c:583
Inline: False
```
**Symbols:**

```
ffffffff811cc330-ffffffff811cc353: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811c9980)
Location: kernel/trace/trace_hwlat.c:582
Inline: False
```
**Symbols:**

```
ffffffff811c9980-ffffffff811c99a3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811cad70)
Location: kernel/trace/trace_hwlat.c:577
Inline: False
```
**Symbols:**

```
ffffffff811cad70-ffffffff811cad93: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811f6f30)
Location: kernel/trace/trace_hwlat.c:825
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff811f6ae0-ffffffff811f6b1c: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff81230750)
Location: kernel/trace/trace_hwlat.c:821
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff81230560-ffffffff812305ac: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8127c870)
Location: kernel/trace/trace_hwlat.c:821
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff8127c810-ffffffff8127c85c: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812943c0)
Location: kernel/trace/trace_hwlat.c:822
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff81294360-ffffffff812943ac: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812afa20)
Location: kernel/trace/trace_hwlat.c:822
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff812af9c0-ffffffff812afa0c: hwlat_tracer_stop (STB_LOCAL)
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
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffff8000102317c0)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffff8000102317c0-ffff8000102317ec: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (c046d2f8)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
c046d2f8-c046d328: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (c0000000002bbcd0)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
c0000000002bbcd0-c0000000002bbd1c: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffe000189302)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffffffe000189302-ffffffe00018932e: hwlat_tracer_stop (STB_LOCAL)
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
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811abac0)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffffffff811abac0-ffffffff811abae3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8119e9b0)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffffffff8119e9b0-ffffffff8119e9d3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811a9890)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffffffff811a9890-ffffffff811a98b3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hwlat_tracer_stop(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811b76d0)
Location: kernel/trace/trace_hwlat.c:569
Inline: False
```
**Symbols:**

```
ffffffff811b76d0-ffffffff811b76f3: hwlat_tracer_stop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
