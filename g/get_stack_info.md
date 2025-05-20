# Function: <code>get_stack_info</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030210)
Location: arch/x86/kernel/dumpstack_64.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81030210-ffffffff81030368: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff8102e470)
Location: arch/x86/kernel/dumpstack_64.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff8102e470-ffffffff8102e5b6: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030300)
Location: arch/x86/kernel/dumpstack_64.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81030300-ffffffff8103045b: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff810316d7-ffffffff810316ef: get_stack_info.cold.0 (STB_LOCAL)
ffffffff81031590-ffffffff810316d7: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81032977-ffffffff8103298f: get_stack_info.cold.0 (STB_LOCAL)
ffffffff81032830-ffffffff81032977: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff8103477c-ffffffff81034794: get_stack_info.cold (STB_LOCAL)
ffffffff81034640-ffffffff8103477c: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81035011-ffffffff81035029: get_stack_info.cold (STB_LOCAL)
ffffffff81034ed0-ffffffff81035011: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81036e7f-ffffffff81036e97: get_stack_info.cold (STB_LOCAL)
ffffffff81036d30-ffffffff81036e7f: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:175
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81bd3391-ffffffff81bd33a9: get_stack_info.cold (STB_LOCAL)
ffffffff81037f00-ffffffff81037f8c: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81bc5803-ffffffff81bc581b: get_stack_info.cold (STB_LOCAL)
ffffffff81039a40-ffffffff81039acc: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81c984e0-ffffffff81c98565: get_stack_info.cold (STB_LOCAL)
ffffffff8103f3d0-ffffffff8103f473: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81e479e4-ffffffff81e47a67: get_stack_info.cold (STB_LOCAL)
ffffffff81046a30-ffffffff81046adb: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff820520c7-ffffffff8205212f: get_stack_info.cold (STB_LOCAL)
ffffffff81050ac0-ffffffff81050b81: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff820d05f2-ffffffff820d0649: get_stack_info.cold (STB_LOCAL)
ffffffff810517f0-ffffffff810518b1: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff821ab107-ffffffff821ab15e: get_stack_info.cold (STB_LOCAL)
ffffffff81058a10-ffffffff81058ad1: get_stack_info (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81035171-ffffffff81035189: get_stack_info.cold (STB_LOCAL)
ffffffff81035030-ffffffff81035171: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81024ab1-ffffffff81024ac9: get_stack_info.cold (STB_LOCAL)
ffffffff81024970-ffffffff81024ab1: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81034fd1-ffffffff81034fe9: get_stack_info.cold (STB_LOCAL)
ffffffff81034e90-ffffffff81034fd1: get_stack_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int get_stack_info(long unsigned int *stack, struct task_struct *task, struct stack_info *info, long unsigned int *visit_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/kernel/dumpstack_64.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:update_stack_state
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
**Symbols:**

```
ffffffff81035f11-ffffffff81035f29: get_stack_info.cold (STB_LOCAL)
ffffffff81035dd0-ffffffff81035f11: get_stack_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
