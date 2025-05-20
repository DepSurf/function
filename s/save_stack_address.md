# Function: <code>save_stack_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void save_stack_address(void *data, long unsigned int addr, int reliable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e5f0)
Location: arch/x86/kernel/stacktrace.c:35
Inline: False
```
**Symbols:**

```
ffffffff8103e5f0-ffffffff8103e622: save_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int save_stack_address(void *data, long unsigned int addr, int reliable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e440)
Location: arch/x86/kernel/stacktrace.c:39
Inline: False
```
**Symbols:**

```
ffffffff8103e440-ffffffff8103e47d: save_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int save_stack_address(struct stack_trace *trace, long unsigned int addr, bool nosched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103dbf0)
Location: arch/x86/kernel/stacktrace.c:13
Inline: True
Direct callers:
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8103dbf0-ffffffff8103dc5e: save_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int save_stack_address(struct stack_trace *trace, long unsigned int addr, bool nosched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103bc80)
Location: arch/x86/kernel/stacktrace.c:15
Inline: True
Direct callers:
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8103bc80-ffffffff8103bcee: save_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int save_stack_address(struct stack_trace *trace, long unsigned int addr, bool nosched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e6a0)
Location: arch/x86/kernel/stacktrace.c:15
Inline: True
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8103e6a0-ffffffff8103e70e: save_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int save_stack_address(struct stack_trace *trace, long unsigned int addr, bool nosched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103fc60)
Location: arch/x86/kernel/stacktrace.c:15
Inline: True
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8103fc60-ffffffff8103fcc1: save_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int save_stack_address(struct stack_trace *trace, long unsigned int addr, bool nosched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81041280)
Location: arch/x86/kernel/stacktrace.c:15
Inline: True
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81041280-ffffffff810412e1: save_stack_address (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct stack_trace *trace</code>
</li>
<li>
<b>Param added. </b>
<code>bool nosched</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>int reliable</code>
</li>
</ul>
</details>
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
