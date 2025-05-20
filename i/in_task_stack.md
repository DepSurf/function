# Function: <code>in_task_stack</code>

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
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810309e0)
Location: arch/x86/kernel/dumpstack.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff810309e0-ffffffff81030a1f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102ecb0)
Location: arch/x86/kernel/dumpstack.c:29
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff8102ecb0-ffffffff8102ecef: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030ba0)
Location: arch/x86/kernel/dumpstack.c:30
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81030ba0-ffffffff81030bdf: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031cd0)
Location: arch/x86/kernel/dumpstack.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81031cd0-ffffffff81031d0f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81032fd0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81032fd0-ffffffff8103300f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81034de0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81034de0-ffffffff81034e1f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035610)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81035610-ffffffff8103564f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037520)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81037520-ffffffff8103755f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c364f0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff81c364f0-ffffffff81c36524: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c28980)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff81c28980-ffffffff81c289b4: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81d46b20)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff81d46b20-ffffffff81d46b54: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81f15030)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff81f15030-ffffffff81f1507c: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff820bc4d0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff820bc4d0-ffffffff820bc51c: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8213dc10)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff8213dc10-ffffffff8213dc5c: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8221fc10)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info_noinstr
```
**Symbols:**

```
ffffffff8221fc10-ffffffff8221fc5c: in_task_stack (STB_GLOBAL)
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
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035770)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff81035770-ffffffff810357af: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810250c0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff810250c0-ffffffff810250ff: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810355d0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff810355d0-ffffffff8103560f: in_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool in_task_stack(long unsigned int *stack, struct task_struct *task, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810365b0)
Location: arch/x86/kernel/dumpstack.c:32
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
```
**Symbols:**

```
ffffffff810365b0-ffffffff810365ef: in_task_stack (STB_GLOBAL)
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
