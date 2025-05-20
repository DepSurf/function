# Function: <code>getreg32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c760)
Location: arch/x86/kernel/ptrace.c:1018
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c760-ffffffff8103c9c6: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c4d0)
Location: arch/x86/kernel/ptrace.c:974
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c4d0-ffffffff8103c734: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bd60)
Location: arch/x86/kernel/ptrace.c:974
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103bd60-ffffffff8103bfbf: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81039da0)
Location: arch/x86/kernel/ptrace.c:975
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81039da0-ffffffff81039ff5: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c7a0)
Location: arch/x86/kernel/ptrace.c:975
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c7a0-ffffffff8103ca04: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103dd30)
Location: arch/x86/kernel/ptrace.c:975
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103dd30-ffffffff8103dfa4: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103f300)
Location: arch/x86/kernel/ptrace.c:966
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103f300-ffffffff8103f574: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041090)
Location: arch/x86/kernel/ptrace.c:938
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81041090-ffffffff810412e0: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041820)
Location: arch/x86/kernel/ptrace.c:938
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81041820-ffffffff81041a70: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045270)
Location: arch/x86/kernel/ptrace.c:953
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81045270-ffffffff810454f1: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044cd0)
Location: arch/x86/kernel/ptrace.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81044cd0-ffffffff81044f56: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81046ca0)
Location: arch/x86/kernel/ptrace.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81046ca0-ffffffff81046f2d: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104d090)
Location: arch/x86/kernel/ptrace.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff8104d090-ffffffff8104d378: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81058260)
Location: arch/x86/kernel/ptrace.c:951
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81058260-ffffffff810584ef: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81065af0)
Location: arch/x86/kernel/ptrace.c:970
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81065af0-ffffffff81065d50: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81067290)
Location: arch/x86/kernel/ptrace.c:970
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81067290-ffffffff81067546: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106e710)
Location: arch/x86/kernel/ptrace.c:971
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff8106e710-ffffffff8106e9c6: getreg32 (STB_LOCAL)
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
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810419a0)
Location: arch/x86/kernel/ptrace.c:938
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff810419a0-ffffffff81041bf0: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81031060)
Location: arch/x86/kernel/ptrace.c:938
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81031060-ffffffff810312b0: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810417e0)
Location: arch/x86/kernel/ptrace.c:938
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff810417e0-ffffffff81041a30: getreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int getreg32(struct task_struct *child, unsigned int regno, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042bc0)
Location: arch/x86/kernel/ptrace.c:938
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_get
```
**Symbols:**

```
ffffffff81042bc0-ffffffff81042e10: getreg32 (STB_LOCAL)
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
