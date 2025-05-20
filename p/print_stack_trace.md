# Function: <code>print_stack_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810ea9d0)
Location: kernel/stacktrace.c:14
Inline: False
```
**Symbols:**

```
ffffffff810ea9d0-ffffffff810eaa4d: print_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810f1670)
Location: kernel/stacktrace.c:14
Inline: False
```
**Symbols:**

```
ffffffff810f1670-ffffffff810f16f6: print_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810f8800)
Location: kernel/stacktrace.c:14
Inline: False
```
**Symbols:**

```
ffffffff810f8800-ffffffff810f8877: print_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810fa830)
Location: kernel/stacktrace.c:14
Inline: True
```
**Symbols:**

```
ffffffff810fa830-ffffffff810fa890: print_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811051b0)
Location: kernel/stacktrace.c:14
Inline: True
```
**Symbols:**

```
ffffffff811051b0-ffffffff81105218: print_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:14
Inline: True
```
**Symbols:**

```
ffffffff81110144-ffffffff8111017f: print_stack_trace.cold.2 (STB_LOCAL)
ffffffff8110ffd0-ffffffff8110ffff: print_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_stack_trace(struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:14
Inline: True
```
**Symbols:**

```
ffffffff8111b784-ffffffff8111b7bf: print_stack_trace.cold.2 (STB_LOCAL)
ffffffff8111b610-ffffffff8111b63f: print_stack_trace (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
