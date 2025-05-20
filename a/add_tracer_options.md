# Function: <code>add_tracer_options</code>

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
In kernel/trace/trace.c (ffffffff81f83bc3)
Location: kernel/trace/trace.c:4357
Inline: True
Inline callers:
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace.c:__update_tracer_options
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
In kernel/trace/trace.c (ffffffff8115ba26)
Location: kernel/trace/trace.c:4754
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
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
In kernel/trace/trace.c (ffffffff81166236)
Location: kernel/trace/trace.c:5003
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
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
In kernel/trace/trace.c (ffffffff81169726)
Location: kernel/trace/trace.c:5320
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
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
In kernel/trace/trace.c (ffffffff811766d6)
Location: kernel/trace/trace.c:5324
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
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
In kernel/trace/trace.c (ffffffff81185876)
Location: kernel/trace/trace.c:5330
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
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
In kernel/trace/trace.c (ffffffff811931a6)
Location: kernel/trace/trace.c:5353
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0c96)
Location: kernel/trace/trace.c:5574
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac6c6)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf0b4)
Location: kernel/trace/trace.c:5830
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff82fe29b7)
Location: kernel/trace/trace.c:5903
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create_dir
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff831ecf51)
Location: kernel/trace/trace.c:6240
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff832d1b22)
Location: kernel/trace/trace.c:6318
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_tracer_options(struct trace_array *tr, struct tracer *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121ef5d)
Location: kernel/trace/trace.c:6332
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8121d870-ffffffff8121d8d3: add_tracer_options (STB_LOCAL)
ffffffff81e65eee-ffffffff81e65f03: add_tracer_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb40cc)
Location: kernel/trace/trace.c:6365
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d93fc)
Location: kernel/trace/trace.c:6488
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390b98c)
Location: kernel/trace/trace.c:6502
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102296d0)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0466cfc)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b0d90)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000183d98)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4ce6)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197c96)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a2ab6)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b0846)
Location: kernel/trace/trace.c:5627
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
