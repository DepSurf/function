# Function: <code>tracing_init_tracefs_percpu</code>

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
In kernel/trace/trace.c (ffffffff81152ad6)
Location: kernel/trace/trace.c:6122
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff8115bcaa)
Location: kernel/trace/trace.c:6525
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811664d8)
Location: kernel/trace/trace.c:6808
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811699fa)
Location: kernel/trace/trace.c:7172
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff81176998)
Location: kernel/trace/trace.c:7175
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff81185bc0)
Location: kernel/trace/trace.c:7263
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff81193518)
Location: kernel/trace/trace.c:7285
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811a101c)
Location: kernel/trace/trace.c:7770
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811aca4c)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tracing_init_tracefs_percpu(struct trace_array *tr, long int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8022
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
**Symbols:**

```
ffffffff811bdfe0-ffffffff811be230: tracing_init_tracefs_percpu (STB_LOCAL)
ffffffff811c51b4-ffffffff811c529c: tracing_init_tracefs_percpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tracing_init_tracefs_percpu(struct trace_array *tr, long int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8096
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
**Symbols:**

```
ffffffff811bbc10-ffffffff811bbe60: tracing_init_tracefs_percpu (STB_LOCAL)
ffffffff81be54f0-ffffffff81be55d8: tracing_init_tracefs_percpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tracing_init_tracefs_percpu(struct trace_array *tr, long int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8432
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
**Symbols:**

```
ffffffff811bb3a0-ffffffff811bb5f0: tracing_init_tracefs_percpu (STB_LOCAL)
ffffffff81bd739e-ffffffff81bd7486: tracing_init_tracefs_percpu.cold (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811e6cf9)
Location: kernel/trace/trace.c:8596
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121ebac)
Location: kernel/trace/trace.c:8628
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff812694fb)
Location: kernel/trace/trace.c:8723
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff81280690)
Location: kernel/trace/trace.c:8886
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff8129a882)
Location: kernel/trace/trace.c:8947
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffff800010229aa0)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (c04670fc)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (c0000000002b1240)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffe00018410e)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811a506c)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff8119801c)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811a2e3c)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
In kernel/trace/trace.c (ffffffff811b0bcc)
Location: kernel/trace/trace.c:7819
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
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
</ul>
