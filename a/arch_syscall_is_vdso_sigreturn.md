# Function: <code>arch_syscall_is_vdso_sigreturn</code>

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
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004e50)
Location: arch/x86/entry/vdso/vma.c:422
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81004e50-ffffffff81004eae: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004df0)
Location: arch/x86/entry/vdso/vma.c:422
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81004df0-ffffffff81004e4e: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005400)
Location: arch/x86/entry/vdso/vma.c:422
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81005400-ffffffff8100545e: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004500)
Location: arch/x86/entry/vdso/vma.c:422
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81004500-ffffffff81004576: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004e80)
Location: arch/x86/entry/vdso/vma.c:399
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81004e80-ffffffff81004ef6: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004680)
Location: arch/x86/entry/vdso/vma.c:400
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81004680-ffffffff810046f6: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006f90)
Location: arch/x86/entry/vdso/vma.c:400
Inline: False
Direct callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81006f90-ffffffff81007006: arch_syscall_is_vdso_sigreturn (STB_GLOBAL)
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
