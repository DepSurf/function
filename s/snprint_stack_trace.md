# Function: <code>snprint_stack_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810eaa50)
Location: kernel/stacktrace.c:28
Inline: False
```
**Symbols:**

```
ffffffff810eaa50-ffffffff810eab15: snprint_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810f1700)
Location: kernel/stacktrace.c:28
Inline: False
```
**Symbols:**

```
ffffffff810f1700-ffffffff810f17b9: snprint_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810f8880)
Location: kernel/stacktrace.c:26
Inline: False
```
**Symbols:**

```
ffffffff810f8880-ffffffff810f8931: snprint_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810fa890)
Location: kernel/stacktrace.c:26
Inline: True
```
**Symbols:**

```
ffffffff810fa890-ffffffff810fa932: snprint_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81105220)
Location: kernel/stacktrace.c:26
Inline: True
```
**Symbols:**

```
ffffffff81105220-ffffffff811052c2: snprint_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81110000)
Location: kernel/stacktrace.c:26
Inline: True
```
**Symbols:**

```
ffffffff81110000-ffffffff811100a2: snprint_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int snprint_stack_trace(char *buf, size_t size, struct stack_trace *trace, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111b640)
Location: kernel/stacktrace.c:26
Inline: True
```
**Symbols:**

```
ffffffff8111b640-ffffffff8111b6e2: snprint_stack_trace (STB_GLOBAL)
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
