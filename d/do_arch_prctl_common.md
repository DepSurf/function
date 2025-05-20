# Function: <code>do_arch_prctl_common</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81036450)
Location: arch/x86/kernel/process.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:compat_SyS_arch_prctl
  - arch/x86/kernel/process_64.c:SyS_arch_prctl
```
**Symbols:**

```
ffffffff81036450-ffffffff810364c5: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810387e0)
Location: arch/x86/kernel/process.c:641
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:compat_SyS_arch_prctl
  - arch/x86/kernel/process_64.c:SyS_arch_prctl
```
**Symbols:**

```
ffffffff810387e0-ffffffff8103887c: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039c90)
Location: arch/x86/kernel/process.c:786
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff81039c90-ffffffff81039d2b: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103b1e0)
Location: arch/x86/kernel/process.c:850
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8103b1e0-ffffffff8103b27b: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d7c0)
Location: arch/x86/kernel/process.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8103d7c0-ffffffff8103d863: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103df80)
Location: arch/x86/kernel/process.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8103df80-ffffffff8103e023: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81041050)
Location: arch/x86/kernel/process.c:973
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff81041050-ffffffff810410f3: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040fb0)
Location: arch/x86/kernel/process.c:973
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff81040fb0-ffffffff81041053: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810429a0)
Location: arch/x86/kernel/process.c:985
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff810429a0-ffffffff81042a43: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81048d10)
Location: arch/x86/kernel/process.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x64_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff81048d10-ffffffff81048db3: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_arch_prctl_common(int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81052060)
Location: arch/x86/kernel/process.c:991
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff81052060-ffffffff8105213a: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_arch_prctl_common(int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f8a0)
Location: arch/x86/kernel/process.c:1006
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8105f8a0-ffffffff8105f97a: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_arch_prctl_common(int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81060ff0)
Location: arch/x86/kernel/process.c:1053
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff81060ff0-ffffffff810610ca: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_arch_prctl_common(int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810680a0)
Location: arch/x86/kernel/process.c:1065
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff810680a0-ffffffff810681d9: do_arch_prctl_common (STB_GLOBAL)
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
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e100)
Location: arch/x86/kernel/process.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8103e100-ffffffff8103e1a3: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102d910)
Location: arch/x86/kernel/process.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8102d910-ffffffff8102d9c3: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103df40)
Location: arch/x86/kernel/process.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8103df40-ffffffff8103dfe3: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct *task, int option, long unsigned int cpuid_enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103f0a0)
Location: arch/x86/kernel/process.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
```
**Symbols:**

```
ffffffff8103f0a0-ffffffff8103f15f: do_arch_prctl_common (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int arg2</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int cpuid_enabled</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, option, cpuid_enabled</code> ➡️ <code>option, arg2</code>
</li>
</ul>
</details>
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
