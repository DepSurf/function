# Function: <code>x86_gsbase_write_cpu_inactive</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102dd60)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
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
In arch/x86/kernel/process_64.c (ffffffff8102fadf)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
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
In arch/x86/kernel/process_64.c (ffffffff8103043f)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
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
In arch/x86/kernel/process_64.c (ffffffff81032c73)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033160)
Location: arch/x86/kernel/process_64.c:423
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81033160-ffffffff810331b9: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034c00)
Location: arch/x86/kernel/process_64.c:423
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81034c00-ffffffff81034c61: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81039f20)
Location: arch/x86/kernel/process_64.c:447
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81039f20-ffffffff81039f81: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81040af0)
Location: arch/x86/kernel/process_64.c:447
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81040af0-ffffffff81040b27: x86_gsbase_write_cpu_inactive.part.0 (STB_LOCAL)
ffffffff81040ee0-ffffffff81040f48: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81049e20)
Location: arch/x86/kernel/process_64.c:447
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81049e20-ffffffff81049e66: x86_gsbase_write_cpu_inactive.part.0 (STB_LOCAL)
ffffffff8104a5d0-ffffffff8104a638: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a440)
Location: arch/x86/kernel/process_64.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8104a440-ffffffff8104a486: x86_gsbase_write_cpu_inactive.part.0 (STB_LOCAL)
ffffffff8104ae10-ffffffff8104ae78: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810516a0)
Location: arch/x86/kernel/process_64.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff810516a0-ffffffff810516e6: x86_gsbase_write_cpu_inactive.part.0 (STB_LOCAL)
ffffffff81052080-ffffffff810520e8: x86_gsbase_write_cpu_inactive (STB_GLOBAL)
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
In arch/x86/kernel/process_64.c (ffffffff8103059f)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
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
In arch/x86/kernel/process_64.c (ffffffff8102001f)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
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
In arch/x86/kernel/process_64.c (ffffffff810303ff)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
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
In arch/x86/kernel/process_64.c (ffffffff81031298)
Location: arch/x86/include/asm/fsgsbase.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
</details>
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
