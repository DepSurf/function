# Function: <code>append_trace_kprobe</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cf9d5)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:587
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811ed940-ffffffff811edb80: append_trace_kprobe (STB_LOCAL)
ffffffff811ee801-ffffffff811ee812: append_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:589
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811ebab0-ffffffff811ebcf0: append_trace_kprobe (STB_LOCAL)
ffffffff81be6423-ffffffff81be6434: append_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:589
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811eacd0-ffffffff811eaebf: append_trace_kprobe (STB_LOCAL)
ffffffff81bd810b-ffffffff81bd811c: append_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:589
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff8121bad0-ffffffff8121bccd: append_trace_kprobe (STB_LOCAL)
ffffffff81cb72cc-ffffffff81cb72dd: append_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:585
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff8125ae60-ffffffff8125b0c2: append_trace_kprobe (STB_LOCAL)
ffffffff81e68359-ffffffff81e6836a: append_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ab520)
Location: kernel/trace/trace_kprobe.c:587
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff812ab520-ffffffff812ab786: append_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812cddb0)
Location: kernel/trace/trace_kprobe.c:587
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff812cddb0-ffffffff812ce027: append_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int append_trace_kprobe(struct trace_kprobe *tk, struct trace_kprobe *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812eb7b0)
Location: kernel/trace/trace_kprobe.c:587
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff812eb7b0-ffffffff812eba27: append_trace_kprobe (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffff800010250218)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
In kernel/trace/trace_kprobe.c (c0483c98)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
In kernel/trace/trace_kprobe.c (c0000000002edf40)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811c7ff5)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811badd5)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811c5dc5)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811d4025)
Location: kernel/trace/trace_kprobe.c:588
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
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
