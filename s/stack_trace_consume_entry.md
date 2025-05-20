# Function: <code>stack_trace_consume_entry</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81125cf0)
Location: kernel/stacktrace.c:81
Inline: True
```
**Symbols:**

```
ffffffff81125cf0-ffffffff81125d38: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81131cc0)
Location: kernel/stacktrace.c:81
Inline: True
```
**Symbols:**

```
ffffffff81131cc0-ffffffff81131d08: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811412ac)
Location: kernel/stacktrace.c:81
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff811410e0-ffffffff81141128: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d54c)
Location: kernel/stacktrace.c:81
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff8113d380-ffffffff8113d3c8: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e79c)
Location: kernel/stacktrace.c:81
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff8113e5d0-ffffffff8113e618: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161c2c)
Location: kernel/stacktrace.c:81
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff81161a60-ffffffff81161aa8: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194b24)
Location: kernel/stacktrace.c:82
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff81194890-ffffffff811948eb: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d27f4)
Location: kernel/stacktrace.c:82
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff811d24d0-ffffffff811d252b: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6ae4)
Location: kernel/stacktrace.c:82
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff811e67c0-ffffffff811e681b: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc914)
Location: kernel/stacktrace.c:82
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_consume_entry_nosched
```
**Symbols:**

```
ffffffff811fc510-ffffffff811fc56b: stack_trace_consume_entry (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a470)
Location: kernel/stacktrace.c:81
Inline: True
```
**Symbols:**

```
ffffffff8112a470-ffffffff8112a4b8: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111cce0)
Location: kernel/stacktrace.c:81
Inline: True
```
**Symbols:**

```
ffffffff8111cce0-ffffffff8111cd28: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81128190)
Location: kernel/stacktrace.c:81
Inline: True
```
**Symbols:**

```
ffffffff81128190-ffffffff811281d8: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81134820)
Location: kernel/stacktrace.c:81
Inline: True
```
**Symbols:**

```
ffffffff81134820-ffffffff81134868: stack_trace_consume_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool reliable</code>
</li>
</ul>
</details>
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
