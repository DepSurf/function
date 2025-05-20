# Function: <code>arch_ftrace_update_trampoline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105b340)
Location: arch/x86/kernel/ftrace.c:823
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
```
**Symbols:**

```
ffffffff8105b340-ffffffff8105b59e: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105b400)
Location: arch/x86/kernel/ftrace.c:829
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
```
**Symbols:**

```
ffffffff8105b400-ffffffff8105b651: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105e240)
Location: arch/x86/kernel/ftrace.c:829
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
```
**Symbols:**

```
ffffffff8105e240-ffffffff8105e491: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105d870)
Location: arch/x86/kernel/ftrace.c:839
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
```
**Symbols:**

```
ffffffff8105d870-ffffffff8105db04: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81061530)
Location: arch/x86/kernel/ftrace.c:840
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
```
**Symbols:**

```
ffffffff81061530-ffffffff810617c4: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81064550)
Location: arch/x86/kernel/ftrace.c:840
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
```
**Symbols:**

```
ffffffff81064550-ffffffff810647ca: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106a1f0)
Location: arch/x86/kernel/ftrace.c:830
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8106a1f0-ffffffff8106a457: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81191230)
Location: arch/x86/kernel/ftrace.c:859
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8106df8e-ffffffff8106dfc7: arch_ftrace_update_trampoline.cold (STB_LOCAL)
ffffffff8106da60-ffffffff8106dd00: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106f080)
Location: arch/x86/kernel/ftrace.c:859
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8106f080-ffffffff8106f30a: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810763c0)
Location: arch/x86/kernel/ftrace.c:469
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff810763c0-ffffffff810764ae: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810769f0)
Location: arch/x86/kernel/ftrace.c:477
Inline: False
```
**Symbols:**

```
ffffffff810769f0-ffffffff81076ade: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81077460)
Location: arch/x86/kernel/ftrace.c:477
Inline: False
```
**Symbols:**

```
ffffffff81077460-ffffffff8107754f: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81084c60)
Location: arch/x86/kernel/ftrace.c:477
Inline: False
```
**Symbols:**

```
ffffffff81084c60-ffffffff81084d4f: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81094e30)
Location: arch/x86/kernel/ftrace.c:469
Inline: False
```
**Symbols:**

```
ffffffff81094e30-ffffffff81094f3d: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810aa8e0)
Location: arch/x86/kernel/ftrace.c:475
Inline: False
```
**Symbols:**

```
ffffffff810aa8e0-ffffffff810aa9ed: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810adc90)
Location: arch/x86/kernel/ftrace.c:474
Inline: False
```
**Symbols:**

```
ffffffff810adc90-ffffffff810add9d: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810b4810)
Location: arch/x86/kernel/ftrace.c:474
Inline: False
```
**Symbols:**

```
ffffffff810b4810-ffffffff810b491d: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010216100)
Location: kernel/trace/ftrace.c:6232
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffff800010216100-ffff800010216104: arch_ftrace_update_trampoline (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454eac)
Location: kernel/trace/ftrace.c:6232
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
c0454eac-c0454ebc: arch_ftrace_update_trampoline (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000297e30)
Location: kernel/trace/ftrace.c:6232
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
c000000000297e30-c000000000297e34: arch_ftrace_update_trampoline (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000175d2c)
Location: kernel/trace/ftrace.c:6232
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffe000175d2c-ffffffe000175d38: arch_ftrace_update_trampoline (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e020)
Location: arch/x86/kernel/ftrace.c:859
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8106e020-ffffffff8106e2aa: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105e440)
Location: arch/x86/kernel/ftrace.c:859
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8105e440-ffffffff8105e6ca: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e4d0)
Location: arch/x86/kernel/ftrace.c:859
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff8106e4d0-ffffffff8106e75a: arch_ftrace_update_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_ftrace_update_trampoline(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81070750)
Location: arch/x86/kernel/ftrace.c:859
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_update_pid_func
  - kernel/trace/ftrace.c:__register_ftrace_function
```
**Symbols:**

```
ffffffff81070750-ffffffff810709da: arch_ftrace_update_trampoline (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
