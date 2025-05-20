# Function: <code>do_set_thread_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d700)
Location: arch/x86/kernel/tls.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_set_thread_area
```
**Symbols:**

```
ffffffff8103d700-ffffffff8103d81e: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d480)
Location: arch/x86/kernel/tls.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_set_thread_area
```
**Symbols:**

```
ffffffff8103d480-ffffffff8103d658: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103cd70)
Location: arch/x86/kernel/tls.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_set_thread_area
```
**Symbols:**

```
ffffffff8103cd70-ffffffff8103cf48: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103adb0)
Location: arch/x86/kernel/tls.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_set_thread_area
```
**Symbols:**

```
ffffffff8103adb0-ffffffff8103af85: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d7e0)
Location: arch/x86/kernel/tls.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_set_thread_area
```
**Symbols:**

```
ffffffff8103d7e0-ffffffff8103d9b5: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103ed40)
Location: arch/x86/kernel/tls.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff8103ed40-ffffffff8103ef10: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81040330)
Location: arch/x86/kernel/tls.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81040330-ffffffff81040507: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff810429e0)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff810429e0-ffffffff81042bab: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81043150)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81043150-ffffffff8104331b: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81046970)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81046970-ffffffff81046b3b: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81046090)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81046090-ffffffff81046253: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81047ab0)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81047ab0-ffffffff81047c73: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8104e340)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff8104e340-ffffffff8104e51c: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81059470)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81059470-ffffffff8105967d: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81066da0)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81066da0-ffffffff81066fad: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81068880)
Location: arch/x86/kernel/tls.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81068880-ffffffff81068a8d: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8106fd00)
Location: arch/x86/kernel/tls.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff8106fd00-ffffffff8106ff0d: do_set_thread_area (STB_GLOBAL)
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
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff810432d0)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff810432d0-ffffffff8104349b: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff810328f0)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff810328f0-ffffffff81032ab9: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81043110)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81043110-ffffffff810432db: do_set_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_set_thread_area(struct task_struct *p, int idx, struct user_desc *u_info, int can_allocate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81044510)
Location: arch/x86/kernel/tls.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_set_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_set_thread_area
```
**Symbols:**

```
ffffffff81044510-ffffffff810446db: do_set_thread_area (STB_GLOBAL)
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
