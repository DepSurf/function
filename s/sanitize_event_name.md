# Function: <code>sanitize_event_name</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81185117)
Location: kernel/trace/trace_kprobe.c:602
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff81192e05)
Location: kernel/trace/trace_kprobe.c:602
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811a876b)
Location: kernel/trace/trace_kprobe.c:643
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811b551d)
Location: kernel/trace/trace_kprobe.c:569
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811c46cf)
Location: kernel/trace/trace_kprobe.c:532
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811d050c)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811ee2fe)
Location: kernel/trace/trace_kprobe.c:705
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811ec48e)
Location: kernel/trace/trace_kprobe.c:707
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811ed12d)
Location: kernel/trace/trace_kprobe.c:707
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff8120af08)
Location: kernel/trace/trace.h:1947
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121e187)
Location: kernel/trace/trace.h:1947
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81246f2c)
Location: kernel/trace/trace.h:1983
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125d78c)
Location: kernel/trace/trace.h:1983
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff812aca9c)
Location: kernel/trace/trace.h:1982
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812d0836)
Location: kernel/trace/trace.h:2015
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e0899)
Location: kernel/trace/trace.h:2015
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ee207)
Location: kernel/trace/trace.h:2036
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_fprobe.c (ffffffff812feb54)
Location: kernel/trace/trace.h:2036
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
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
In kernel/trace/trace_kprobe.c (ffff800010250c80)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (c048432c)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8b2c)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811bb90c)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811c68fc)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811d4b5c)
Location: kernel/trace/trace_kprobe.c:706
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
</details>
</li>
</ul>

## Differences
