# Function: <code>do_get_thread_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d850)
Location: arch/x86/kernel/tls.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_get_thread_area
```
**Symbols:**

```
ffffffff8103d850-ffffffff8103d8dc: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d690)
Location: arch/x86/kernel/tls.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_get_thread_area
```
**Symbols:**

```
ffffffff8103d690-ffffffff8103d71c: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103cf80)
Location: arch/x86/kernel/tls.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_get_thread_area
```
**Symbols:**

```
ffffffff8103cf80-ffffffff8103d00c: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103afc0)
Location: arch/x86/kernel/tls.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_get_thread_area
```
**Symbols:**

```
ffffffff8103afc0-ffffffff8103b04d: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d9f0)
Location: arch/x86/kernel/tls.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:SyS_get_thread_area
```
**Symbols:**

```
ffffffff8103d9f0-ffffffff8103da7d: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103ef70)
Location: arch/x86/kernel/tls.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff8103ef70-ffffffff8103efff: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81040570)
Location: arch/x86/kernel/tls.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81040570-ffffffff810405ff: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81042c10)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81042c10-ffffffff81042cab: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81043380)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81043380-ffffffff8104341b: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81046858)
Location: arch/x86/kernel/tls.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81046ba0-ffffffff81046ce7: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff810462c0)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff810462c0-ffffffff81046407: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81047ce0)
Location: arch/x86/kernel/tls.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81047ce0-ffffffff81047e26: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8104e580)
Location: arch/x86/kernel/tls.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff8104e580-ffffffff8104e6f2: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81059700)
Location: arch/x86/kernel/tls.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81059700-ffffffff81059891: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81067060)
Location: arch/x86/kernel/tls.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81067060-ffffffff810671f1: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff810687ad)
Location: arch/x86/kernel/tls.c:215
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81068b40-ffffffff81068c34: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8106fc2d)
Location: arch/x86/kernel/tls.c:215
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8106ffc0-ffffffff810700b4: do_get_thread_area (STB_GLOBAL)
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
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81043500)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81043500-ffffffff8104359b: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81032b20)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81032b20-ffffffff81032bbb: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81043340)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81043340-ffffffff810433db: do_get_thread_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_get_thread_area(struct task_struct *p, int idx, struct user_desc *u_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81044740)
Location: arch/x86/kernel/tls.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
**Symbols:**

```
ffffffff81044740-ffffffff810447db: do_get_thread_area (STB_GLOBAL)
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
