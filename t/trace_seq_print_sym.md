# Function: <code>trace_seq_print_sym</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c4240)
Location: kernel/trace/trace_output.c:357
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff811c4240-ffffffff811c4313: trace_seq_print_sym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c5190)
Location: kernel/trace/trace_output.c:367
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff811c5190-ffffffff811c5269: trace_seq_print_sym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811f06d0)
Location: kernel/trace/trace_output.c:367
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff811f06d0-ffffffff811f07a9: trace_seq_print_sym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff81e66891-ffffffff81e668a9: trace_seq_print_sym.cold (STB_LOCAL)
ffffffff81228e00-ffffffff81228f02: trace_seq_print_sym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81274450)
Location: kernel/trace/trace_output.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff81274450-ffffffff81274562: trace_seq_print_sym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8128bbf0)
Location: kernel/trace/trace_output.c:361
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff8128bbf0-ffffffff8128bd1b: trace_seq_print_sym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_seq_print_sym(struct trace_seq *s, long unsigned int address, bool offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812a6fc0)
Location: kernel/trace/trace_output.c:361
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
**Symbols:**

```
ffffffff812a6fc0-ffffffff812a70eb: trace_seq_print_sym (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
