# Function: <code>on_stack</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069a71)
Location: arch/x86/include/asm/stacktrace.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
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
In arch/x86/kernel/unwind_frame.c (ffffffff81068e06)
Location: arch/x86/include/asm/stacktrace.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030c95)
Location: arch/x86/include/asm/stacktrace.h:39
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d686)
Location: arch/x86/include/asm/stacktrace.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031f81)
Location: arch/x86/include/asm/stacktrace.h:39
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107085c)
Location: arch/x86/include/asm/stacktrace.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81033246)
Location: arch/x86/include/asm/stacktrace.h:39
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107684e)
Location: arch/x86/include/asm/stacktrace.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810350bc)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a3ee)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810358ec)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b4de)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool on_stack(struct stack_info *info, void *addr, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810377e9)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: False
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8108290a)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff810377e9-ffffffff8103781d: on_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool on_stack(struct stack_info *info, void *addr, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd33c5)
Location: arch/x86/include/asm/stacktrace.h:43
Inline: False
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810823ba)
Location: arch/x86/include/asm/stacktrace.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81bd33c5-ffffffff81bd33f9: on_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool on_stack(struct stack_info *info, void *addr, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5837)
Location: arch/x86/include/asm/stacktrace.h:43
Inline: False
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810831da)
Location: arch/x86/include/asm/stacktrace.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81bc5837-ffffffff81bc586c: on_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool on_stack(struct stack_info *info, void *addr, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c98581)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: False
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810922da)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81c98581-ffffffff81c985b6: on_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool on_stack(struct stack_info *info, void *addr, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e47a81)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: False
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810a355a)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81e47a81-ffffffff81e47ac2: on_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810515ca)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb97a)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8105232a)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810beaba)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8105954a)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810c5c3a)
Location: arch/x86/include/asm/stacktrace.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035a4c)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a4de)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102539c)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81069c0e)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810358ac)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a48e)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103688c)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c58e)
Location: arch/x86/include/asm/stacktrace.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
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
</ul>
