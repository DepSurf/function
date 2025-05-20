# Function: <code>arch_stack_walk_user</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81043b40)
Location: arch/x86/kernel/stacktrace.c:115
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81043b40-ffffffff81043c37: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044290)
Location: arch/x86/kernel/stacktrace.c:115
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81044290-ffffffff81044387: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81047fa0)
Location: arch/x86/kernel/stacktrace.c:112
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81047fa0-ffffffff8104804d: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81047450)
Location: arch/x86/kernel/stacktrace.c:112
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81047450-ffffffff810474f9: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81048d50)
Location: arch/x86/kernel/stacktrace.c:106
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81048d50-ffffffff81048e29: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8104f740)
Location: arch/x86/kernel/stacktrace.c:106
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff8104f740-ffffffff8104f819: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8105aa60)
Location: arch/x86/kernel/stacktrace.c:106
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff8105aa60-ffffffff8105ab74: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81068830)
Location: arch/x86/kernel/stacktrace.c:106
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81068830-ffffffff81068944: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8106a150)
Location: arch/x86/kernel/stacktrace.c:106
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff8106a150-ffffffff8106a21e: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81071620)
Location: arch/x86/kernel/stacktrace.c:106
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81071620-ffffffff810716ee: arch_stack_walk_user (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044410)
Location: arch/x86/kernel/stacktrace.c:115
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81044410-ffffffff81044507: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81033a30)
Location: arch/x86/kernel/stacktrace.c:115
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81033a30-ffffffff81033b27: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044250)
Location: arch/x86/kernel/stacktrace.c:115
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81044250-ffffffff81044347: arch_stack_walk_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void *cookie, const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81045650)
Location: arch/x86/kernel/stacktrace.c:115
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
**Symbols:**

```
ffffffff81045650-ffffffff81045747: arch_stack_walk_user (STB_GLOBAL)
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
