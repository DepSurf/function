# Function: <code>arch_ptrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103cb60)
Location: arch/x86/kernel/ptrace.c:813
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8103cb60-ffffffff8103ce47: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c8d0)
Location: arch/x86/kernel/ptrace.c:766
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8103c8d0-ffffffff8103cba7: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c150)
Location: arch/x86/kernel/ptrace.c:766
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8103c150-ffffffff8103c473: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103a190)
Location: arch/x86/kernel/ptrace.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8103a190-ffffffff8103a48e: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103cba0)
Location: arch/x86/kernel/ptrace.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8103cba0-ffffffff8103ceac: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e130)
Location: arch/x86/kernel/ptrace.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8103e130-ffffffff8103e43a: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103f710)
Location: arch/x86/kernel/ptrace.c:758
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8103f710-ffffffff8103fa68: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041de0)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81041de0-ffffffff8104213b: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042560)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81042560-ffffffff810428bb: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045d20)
Location: arch/x86/kernel/ptrace.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81045d20-ffffffff810460f4: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810457a0)
Location: arch/x86/kernel/ptrace.c:708
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810457a0-ffffffff81045bba: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810472e0)
Location: arch/x86/kernel/ptrace.c:711
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810472e0-ffffffff810475a9: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104db00)
Location: arch/x86/kernel/ptrace.c:711
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8104db00-ffffffff8104de06: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81058ab0)
Location: arch/x86/kernel/ptrace.c:710
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81058ab0-ffffffff81058e3f: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066380)
Location: arch/x86/kernel/ptrace.c:729
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81066380-ffffffff8106670f: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81067b70)
Location: arch/x86/kernel/ptrace.c:729
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81067b70-ffffffff81067ec3: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106eff0)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8106eff0-ffffffff8106f343: arch_ptrace (STB_GLOBAL)
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
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008ec28)
Location: arch/arm64/kernel/ptrace.c:1797
Inline: False
Direct callers:
  - kernel/ptrace.c:__arm64_sys_ptrace
```
**Symbols:**

```
ffff80001008ec28-ffff80001008ec78: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030c87c)
Location: arch/arm/kernel/ptrace.c:784
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
c030c87c-c030ce6c: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000018a30)
Location: arch/powerpc/kernel/ptrace.c:2983
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
c000000000018a30-c00000000001920c: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/ptrace.c (ffffffe0000b62c4)
Location: arch/riscv/kernel/ptrace.c:133
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
ffffffe0000b62c4-ffffffe0000b6306: arch_ptrace (STB_GLOBAL)
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
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810426e0)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810426e0-ffffffff81042a3b: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81031da0)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81031da0-ffffffff810320b0: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042520)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81042520-ffffffff8104287b: arch_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81043900)
Location: arch/x86/kernel/ptrace.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81043900-ffffffff81043c5b: arch_ptrace (STB_GLOBAL)
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
