# Function: <code>local_db_save</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbd6c9)
Location: arch/x86/include/asm/debugreg.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbde52)
Location: arch/x86/include/asm/debugreg.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbeb00)
Location: arch/x86/include/asm/debugreg.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c35d1d)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c3674c)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37300)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c281bd)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c28bdc)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29a60)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d4632d)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81d46d79)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47fd0)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f145ec)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81f152ba)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16ad0)
Location: arch/x86/include/asm/debugreg.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820bb95c)
Location: arch/x86/include/asm/debugreg.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff820bc74a)
Location: arch/x86/include/asm/debugreg.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820be0b0)
Location: arch/x86/include/asm/debugreg.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213d08c)
Location: arch/x86/include/asm/debugreg.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8213dee4)
Location: arch/x86/include/asm/debugreg.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213fb50)
Location: arch/x86/include/asm/debugreg.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221f0ac)
Location: arch/x86/include/asm/debugreg.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8221fee0)
Location: arch/x86/include/asm/debugreg.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221b70)
Location: arch/x86/include/asm/debugreg.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
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
