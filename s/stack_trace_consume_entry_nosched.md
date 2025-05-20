# Function: <code>stack_trace_consume_entry_nosched</code>

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
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81125e90)
Location: kernel/stacktrace.c:97
Inline: True
```
**Symbols:**

```
ffffffff81125e90-ffffffff81125ef3: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81131e50)
Location: kernel/stacktrace.c:97
Inline: True
```
**Symbols:**

```
ffffffff81131e50-ffffffff81131eb3: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81141280)
Location: kernel/stacktrace.c:97
Inline: False
```
**Symbols:**

```
ffffffff81141280-ffffffff811412e8: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d520)
Location: kernel/stacktrace.c:96
Inline: False
```
**Symbols:**

```
ffffffff8113d520-ffffffff8113d588: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e770)
Location: kernel/stacktrace.c:96
Inline: False
```
**Symbols:**

```
ffffffff8113e770-ffffffff8113e7d8: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161c00)
Location: kernel/stacktrace.c:96
Inline: False
```
**Symbols:**

```
ffffffff81161c00-ffffffff81161c68: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194af0)
Location: kernel/stacktrace.c:97
Inline: False
```
**Symbols:**

```
ffffffff81194af0-ffffffff81194b64: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d27c0)
Location: kernel/stacktrace.c:97
Inline: False
```
**Symbols:**

```
ffffffff811d27c0-ffffffff811d2834: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6ab0)
Location: kernel/stacktrace.c:97
Inline: False
```
**Symbols:**

```
ffffffff811e6ab0-ffffffff811e6b24: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc8e0)
Location: kernel/stacktrace.c:97
Inline: False
```
**Symbols:**

```
ffffffff811fc8e0-ffffffff811fc954: stack_trace_consume_entry_nosched (STB_LOCAL)
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
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a600)
Location: kernel/stacktrace.c:97
Inline: True
```
**Symbols:**

```
ffffffff8112a600-ffffffff8112a663: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111ce70)
Location: kernel/stacktrace.c:97
Inline: True
```
**Symbols:**

```
ffffffff8111ce70-ffffffff8111ced3: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81128320)
Location: kernel/stacktrace.c:97
Inline: True
```
**Symbols:**

```
ffffffff81128320-ffffffff81128383: stack_trace_consume_entry_nosched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool stack_trace_consume_entry_nosched(void *cookie, long unsigned int addr, bool reliable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811349b0)
Location: kernel/stacktrace.c:97
Inline: True
```
**Symbols:**

```
ffffffff811349b0-ffffffff81134a13: stack_trace_consume_entry_nosched (STB_LOCAL)
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
