# Function: <code>compat_arch_ptrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ce50)
Location: arch/x86/kernel/ptrace.c:1280
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8103ce50-ffffffff8103d2bc: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103cbb0)
Location: arch/x86/kernel/ptrace.c:1236
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8103cbb0-ffffffff8103d004: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c480)
Location: arch/x86/kernel/ptrace.c:1236
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8103c480-ffffffff8103c915: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103a490)
Location: arch/x86/kernel/ptrace.c:1237
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8103a490-ffffffff8103a955: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ceb0)
Location: arch/x86/kernel/ptrace.c:1237
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8103ceb0-ffffffff8103d388: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e440)
Location: arch/x86/kernel/ptrace.c:1237
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff8103e440-ffffffff8103e924: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103fa70)
Location: arch/x86/kernel/ptrace.c:1228
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff8103fa70-ffffffff8103ff72: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042140)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff81042140-ffffffff81042609: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810428c0)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff810428c0-ffffffff81042d89: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81046310)
Location: arch/x86/kernel/ptrace.c:1215
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff81046310-ffffffff81046336: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045db0)
Location: arch/x86/kernel/ptrace.c:1190
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff81045db0-ffffffff81045dd6: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810477d0)
Location: arch/x86/kernel/ptrace.c:1201
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff810477d0-ffffffff810477f6: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104e030)
Location: arch/x86/kernel/ptrace.c:1201
Inline: False
Direct callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff8104e030-ffffffff8104e056: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810590c0)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff810590c0-ffffffff810590dc: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810669b0)
Location: arch/x86/kernel/ptrace.c:1219
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff810669b0-ffffffff810669cc: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810680e0)
Location: arch/x86/kernel/ptrace.c:1219
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff810680e0-ffffffff810680fc: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106f560)
Location: arch/x86/kernel/ptrace.c:1220
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff8106f560-ffffffff8106f57c: compat_arch_ptrace (STB_GLOBAL)
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
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008e5e8)
Location: arch/arm64/kernel/ptrace.c:1701
Inline: False
Direct callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
```
**Symbols:**

```
ffff80001008e5e8-ffff80001008ebc0: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace32.c (c000000000034fb0)
Location: arch/powerpc/kernel/ptrace32.c:47
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
```
**Symbols:**

```
c000000000034fb0-c0000000000359f8: compat_arch_ptrace (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042a40)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff81042a40-ffffffff81042f09: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810320b0)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff810320b0-ffffffff81032523: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042880)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff81042880-ffffffff81042d49: compat_arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81043c60)
Location: arch/x86/kernel/ptrace.c:1200
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
```
**Symbols:**

```
ffffffff81043c60-ffffffff81044129: compat_arch_ptrace (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
