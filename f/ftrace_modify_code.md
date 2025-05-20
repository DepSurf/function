# Function: <code>ftrace_modify_code</code>

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
In arch/x86/kernel/ftrace.c (ffffffff8105acfc)
Location: arch/x86/kernel/ftrace.c:604
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
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
In arch/x86/kernel/ftrace.c (ffffffff8105ad8c)
Location: arch/x86/kernel/ftrace.c:611
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
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
In arch/x86/kernel/ftrace.c (ffffffff8105dbcc)
Location: arch/x86/kernel/ftrace.c:611
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
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
In arch/x86/kernel/ftrace.c (ffffffff8105d27c)
Location: arch/x86/kernel/ftrace.c:617
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
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
In arch/x86/kernel/ftrace.c (ffffffff81060f1c)
Location: arch/x86/kernel/ftrace.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
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
In arch/x86/kernel/ftrace.c (ffffffff8106403c)
Location: arch/x86/kernel/ftrace.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
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
In arch/x86/kernel/ftrace.c (ffffffff81069ce7)
Location: arch/x86/kernel/ftrace.c:621
Inline: True
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
In arch/x86/kernel/ftrace.c (ffffffff8106d598)
Location: arch/x86/kernel/ftrace.c:644
Inline: True
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
In arch/x86/kernel/ftrace.c (ffffffff8106eb98)
Location: arch/x86/kernel/ftrace.c:644
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ftrace_modify_code(long unsigned int pc, u32 old, u32 new, bool validate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ftrace.c (ffff8000100a18bc)
Location: arch/arm64/kernel/ftrace.c:24
Inline: True
Inline callers:
  - arch/arm64/kernel/ftrace.c:ftrace_update_ftrace_func
Direct callers:
  - arch/arm64/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/arm64/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/arm64/kernel/ftrace.c:ftrace_make_nop
  - arch/arm64/kernel/ftrace.c:ftrace_make_call
```
**Symbols:**

```
ffff8000100a1800-ffff8000100a1898: ftrace_modify_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_modify_code(long unsigned int pc, long unsigned int old, long unsigned int new, bool validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ftrace.c (c0314c84)
Location: arch/arm/kernel/ftrace.c:79
Inline: False
Direct callers:
  - arch/arm/kernel/ftrace.c:__ftrace_modify_caller
  - arch/arm/kernel/ftrace.c:ftrace_make_nop
  - arch/arm/kernel/ftrace.c:ftrace_modify_call
  - arch/arm/kernel/ftrace.c:ftrace_make_call
  - arch/arm/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/arm/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
c0314c84-c0314d44: ftrace_modify_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ftrace_modify_code(long unsigned int ip, unsigned int old, unsigned int new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/trace/ftrace.c (c000000000073030)
Location: arch/powerpc/kernel/trace/ftrace.c:57
Inline: False
Direct callers:
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_update_ftrace_func
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_update_ftrace_func
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
```
**Symbols:**

```
c000000000073030-c000000000073110: ftrace_modify_code (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff8106db38)
Location: arch/x86/kernel/ftrace.c:644
Inline: True
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
In arch/x86/kernel/ftrace.c (ffffffff8105df58)
Location: arch/x86/kernel/ftrace.c:644
Inline: True
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
In arch/x86/kernel/ftrace.c (ffffffff8106dfe8)
Location: arch/x86/kernel/ftrace.c:644
Inline: True
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
In arch/x86/kernel/ftrace.c (ffffffff81070268)
Location: arch/x86/kernel/ftrace.c:644
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
