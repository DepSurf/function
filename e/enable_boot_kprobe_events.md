# Function: <code>enable_boot_kprobe_events</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff828cec6b)
Location: kernel/trace/trace_kprobe.c:1448
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff828d7147)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enable_boot_kprobe_events();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff82cf6c96)
Location: kernel/trace/trace_kprobe.c:1842
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff82cf6c96-ffffffff82cf6d45: enable_boot_kprobe_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enable_boot_kprobe_events();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff82fe379d)
Location: kernel/trace/trace_kprobe.c:1863
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff82fe379d-ffffffff82fe384c: enable_boot_kprobe_events (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff831edfc9)
Location: kernel/trace/trace_kprobe.c:1866
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff832d2c8f)
Location: kernel/trace/trace_kprobe.c:1864
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff834870d4)
Location: kernel/trace/trace_kprobe.c:1858
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff83eb6b22)
Location: kernel/trace/trace_kprobe.c:1810
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff836dc102)
Location: kernel/trace/trace_kprobe.c:1767
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff8390e732)
Location: kernel/trace/trace_kprobe.c:1850
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffff80001144fb10)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (c152a2d0)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (c000000001376df0)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff828bfff8)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff828b8698)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff828d2d7b)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
In kernel/trace/trace_kprobe.c (ffffffff828d819c)
Location: kernel/trace/trace_kprobe.c:1649
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
</ul>
