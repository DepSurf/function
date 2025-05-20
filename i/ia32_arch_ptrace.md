# Function: <code>ia32_arch_ptrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ce9b)
Location: arch/x86/kernel/ptrace.c:1124
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103cbfb)
Location: arch/x86/kernel/ptrace.c:1080
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c4b4)
Location: arch/x86/kernel/ptrace.c:1080
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103a4ca)
Location: arch/x86/kernel/ptrace.c:1081
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103cee7)
Location: arch/x86/kernel/ptrace.c:1081
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e477)
Location: arch/x86/kernel/ptrace.c:1081
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103faaa)
Location: arch/x86/kernel/ptrace.c:1072
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff81042179)
Location: arch/x86/kernel/ptrace.c:1044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff810428f9)
Location: arch/x86/kernel/ptrace.c:1044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81046100)
Location: arch/x86/kernel/ptrace.c:1059
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81046100-ffffffff8104630d: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045bc0)
Location: arch/x86/kernel/ptrace.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81045bc0-ffffffff81045da6: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810475b0)
Location: arch/x86/kernel/ptrace.c:1045
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff810475b0-ffffffff810477cf: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104de10)
Location: arch/x86/kernel/ptrace.c:1045
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8104de10-ffffffff8104e02f: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81058e40)
Location: arch/x86/kernel/ptrace.c:1044
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81058e40-ffffffff810590b8: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066720)
Location: arch/x86/kernel/ptrace.c:1063
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81066720-ffffffff81066998: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81067ee0)
Location: arch/x86/kernel/ptrace.c:1063
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff81067ee0-ffffffff810680c9: ia32_arch_ptrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int ia32_arch_ptrace(struct task_struct *child, compat_long_t request, compat_ulong_t caddr, compat_ulong_t cdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106f360)
Location: arch/x86/kernel/ptrace.c:1064
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8106f360-ffffffff8106f549: ia32_arch_ptrace (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042a79)
Location: arch/x86/kernel/ptrace.c:1044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff810320e9)
Location: arch/x86/kernel/ptrace.c:1044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff810428b9)
Location: arch/x86/kernel/ptrace.c:1044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff81043c99)
Location: arch/x86/kernel/ptrace.c:1044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
