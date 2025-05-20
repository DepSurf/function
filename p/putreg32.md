# Function: <code>putreg32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c400)
Location: arch/x86/kernel/ptrace.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c400-ffffffff8103c5d7: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c140)
Location: arch/x86/kernel/ptrace.c:901
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c140-ffffffff8103c317: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b740)
Location: arch/x86/kernel/ptrace.c:901
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103b740-ffffffff8103b916: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81039780)
Location: arch/x86/kernel/ptrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81039780-ffffffff81039956: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c180)
Location: arch/x86/kernel/ptrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c180-ffffffff8103c360: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d670)
Location: arch/x86/kernel/ptrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103d670-ffffffff8103d854: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ec00)
Location: arch/x86/kernel/ptrace.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103ec00-ffffffff8103ede4: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810418e0)
Location: arch/x86/kernel/ptrace.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff810418e0-ffffffff81041add: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042060)
Location: arch/x86/kernel/ptrace.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81042060-ffffffff8104225d: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810455d0)
Location: arch/x86/kernel/ptrace.c:880
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff810455d0-ffffffff8104582b: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045000)
Location: arch/x86/kernel/ptrace.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81045000-ffffffff810452ee: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81046750)
Location: arch/x86/kernel/ptrace.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81046750-ffffffff810469d2: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104d6c0)
Location: arch/x86/kernel/ptrace.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff8104d6c0-ffffffff8104d9a2: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810585b0)
Location: arch/x86/kernel/ptrace.c:853
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff810585b0-ffffffff8105891c: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81065e30)
Location: arch/x86/kernel/ptrace.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81065e30-ffffffff8106619c: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81067630)
Location: arch/x86/kernel/ptrace.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81067630-ffffffff81067984: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106eab0)
Location: arch/x86/kernel/ptrace.c:873
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff8106eab0-ffffffff8106ee04: putreg32 (STB_LOCAL)
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
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810421e0)
Location: arch/x86/kernel/ptrace.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff810421e0-ffffffff810423dd: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810318a0)
Location: arch/x86/kernel/ptrace.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff810318a0-ffffffff81031a9d: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042020)
Location: arch/x86/kernel/ptrace.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81042020-ffffffff8104221d: putreg32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int putreg32(struct task_struct *child, unsigned int regno, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81043400)
Location: arch/x86/kernel/ptrace.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs32_set
```
**Symbols:**

```
ffffffff81043400-ffffffff810435fd: putreg32 (STB_LOCAL)
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
