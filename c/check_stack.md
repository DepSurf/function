# Function: <code>check_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811581d0)
Location: kernel/trace/trace_stack.c:75
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811581d0-ffffffff81158497: check_stack (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81162a60)
Location: kernel/trace/trace_stack.c:75
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81162a60-ffffffff81162d2d: check_stack (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8116dd90)
Location: kernel/trace/trace_stack.c:75
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8116dd90-ffffffff8116e05c: check_stack (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81171080)
Location: kernel/trace/trace_stack.c:76
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81171080-ffffffff81171392: check_stack (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8117e240)
Location: kernel/trace/trace_stack.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8117e240-ffffffff8117e51b: check_stack (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8118d737-ffffffff8118d73e: check_stack.cold.4 (STB_LOCAL)
ffffffff8118d2f0-ffffffff8118d5b3: check_stack (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8119b0b7-ffffffff8119b0be: check_stack.cold.5 (STB_LOCAL)
ffffffff8119ac70-ffffffff8119af31: check_stack (STB_WEAK)
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
In kernel/trace/trace_stack.c (ffffffff811a885d)
Location: kernel/trace/trace_stack.c:56
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In kernel/trace/trace_stack.c (ffffffff811b407d)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811cc870-ffffffff811ccae0: check_stack (STB_LOCAL)
ffffffff811ccd6c-ffffffff811ccdbe: check_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811c9db0-ffffffff811ca020: check_stack (STB_LOCAL)
ffffffff81be5cd3-ffffffff81be5d25: check_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811cb160-ffffffff811cb3df: check_stack (STB_LOCAL)
ffffffff81bd7aec-ffffffff81bd7b3e: check_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811f7470-ffffffff811f7869: check_stack (STB_LOCAL)
ffffffff81cb5f48-ffffffff81cb603c: check_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81230fe0-ffffffff81231401: check_stack (STB_LOCAL)
ffffffff81e66f67-ffffffff81e67058: check_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8127d450)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8127d450-ffffffff8127d96b: check_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81299ef0)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81299ef0-ffffffff8129a3ee: check_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_stack(long unsigned int ip, long unsigned int *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff812b5570)
Location: kernel/trace/trace_stack.c:155
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff812b5570-ffffffff812b5a6e: check_stack (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffff800010232474)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (c046e11c)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (c0000000002bcd44)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffe000189bd6)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
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
In kernel/trace/trace_stack.c (ffffffff811ac69d)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In kernel/trace/trace_stack.c (ffffffff8119f3ed)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In kernel/trace/trace_stack.c (ffffffff811aa46d)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In kernel/trace/trace_stack.c (ffffffff811b82c1)
Location: kernel/trace/trace_stack.c:155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
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
