# Function: <code>mmio_print_rw</code>

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
In kernel/trace/trace_mmiotrace.c (ffffffff8115865a)
Location: kernel/trace/trace_mmiotrace.c:170
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff81162f89)
Location: kernel/trace/trace_mmiotrace.c:166
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff8116e2b9)
Location: kernel/trace/trace_mmiotrace.c:166
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff811715a1)
Location: kernel/trace/trace_mmiotrace.c:166
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff8117e731)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff8118d779)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff8119b0f9)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff811a8ccd)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff811b44e9)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811ccdc0)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff811ccdc0-ffffffff811ccee9: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811ca2b0)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff811ca2b0-ffffffff811ca3d9: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811cb680)
Location: kernel/trace/trace_mmiotrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff811cb680-ffffffff811cb7a9: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811f7b10)
Location: kernel/trace/trace_mmiotrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff811f7b10-ffffffff811f7c39: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff81231730)
Location: kernel/trace/trace_mmiotrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff81231730-ffffffff81231885: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff8127dcf0)
Location: kernel/trace/trace_mmiotrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff8127dcf0-ffffffff8127de45: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff8129a770)
Location: kernel/trace/trace_mmiotrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff8129a770-ffffffff8129a8c9: mmio_print_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum print_line_t mmio_print_rw(struct trace_iterator *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff812b5df0)
Location: kernel/trace/trace_mmiotrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff812b5df0-ffffffff812b5f49: mmio_print_rw (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811acb09)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff8119f999)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff811aa8d9)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
In kernel/trace/trace_mmiotrace.c (ffffffff811b8739)
Location: kernel/trace/trace_mmiotrace.c:167
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
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
