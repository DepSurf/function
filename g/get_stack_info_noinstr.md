# Function: <code>get_stack_info_noinstr</code>

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
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81c36400)
Location: arch/x86/kernel/dumpstack_64.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81c36400-ffffffff81c364ea: get_stack_info_noinstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81c28890)
Location: arch/x86/kernel/dumpstack_64.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81c28890-ffffffff81c2897d: get_stack_info_noinstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81d46a00)
Location: arch/x86/kernel/dumpstack_64.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81d46a00-ffffffff81d46b14: get_stack_info_noinstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81f14f10)
Location: arch/x86/kernel/dumpstack_64.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81f14f10-ffffffff81f15022: get_stack_info_noinstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff820bc3a0)
Location: arch/x86/kernel/dumpstack_64.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff820bc3a0-ffffffff820bc4b2: get_stack_info_noinstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff8213dae0)
Location: arch/x86/kernel/dumpstack_64.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff8213dae0-ffffffff8213dbf2: get_stack_info_noinstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool get_stack_info_noinstr(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff8221fae0)
Location: arch/x86/kernel/dumpstack_64.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:vc_switch_off_ist
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff8221fae0-ffffffff8221fbf2: get_stack_info_noinstr (STB_GLOBAL)
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
