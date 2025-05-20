# Function: <code>ptrace_get_debugreg</code>

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
In arch/x86/kernel/ptrace.c (ffffffff8103c8ba)
Location: arch/x86/kernel/ptrace.c:696
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff8103cdff)
Location: arch/x86/kernel/ptrace.c:649
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff8103c827)
Location: arch/x86/kernel/ptrace.c:649
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff8103a738)
Location: arch/x86/kernel/ptrace.c:650
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff8103d165)
Location: arch/x86/kernel/ptrace.c:650
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff8103e72b)
Location: arch/x86/kernel/ptrace.c:650
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff8103fef3)
Location: arch/x86/kernel/ptrace.c:641
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810423ee)
Location: arch/x86/kernel/ptrace.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81041060-ffffffff81041090: ptrace_get_debugreg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042b6e)
Location: arch/x86/kernel/ptrace.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810417f0-ffffffff81041820: ptrace_get_debugreg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045bfd)
Location: arch/x86/kernel/ptrace.c:627
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104566a)
Location: arch/x86/kernel/ptrace.c:592
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810471db)
Location: arch/x86/kernel/ptrace.c:592
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104d642)
Location: arch/x86/kernel/ptrace.c:592
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8105830d)
Location: arch/x86/kernel/ptrace.c:591
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81065b8c)
Location: arch/x86/kernel/ptrace.c:610
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106740e)
Location: arch/x86/kernel/ptrace.c:610
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106e88e)
Location: arch/x86/kernel/ptrace.c:611
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042cee)
Location: arch/x86/kernel/ptrace.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81041970-ffffffff810419a0: ptrace_get_debugreg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103232a)
Location: arch/x86/kernel/ptrace.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81031030-ffffffff81031060: ptrace_get_debugreg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042b2e)
Location: arch/x86/kernel/ptrace.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810417b0-ffffffff810417e0: ptrace_get_debugreg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81043f0e)
Location: arch/x86/kernel/ptrace.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81042b90-ffffffff81042bc0: ptrace_get_debugreg.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
