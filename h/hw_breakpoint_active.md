# Function: <code>hw_breakpoint_active</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810398a5)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
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
In arch/x86/kernel/alternative.c (ffffffff8103a076)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbd6ce)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbde57)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cce4)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbeb11)
Location: arch/x86/include/asm/debugreg.h:88
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
In arch/x86/kernel/traps.c (ffffffff81c35d22)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c36751)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d1a8)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37311)
Location: arch/x86/include/asm/debugreg.h:88
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
In arch/x86/kernel/traps.c (ffffffff81c281c2)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c28be1)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e9e5)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29a71)
Location: arch/x86/include/asm/debugreg.h:88
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
In arch/x86/kernel/traps.c (ffffffff81d46332)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81d46d7e)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff81044755)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47fe1)
Location: arch/x86/include/asm/debugreg.h:88
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
In arch/x86/kernel/traps.c (ffffffff81f145f1)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81f152bf)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8104cd4d)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16ae1)
Location: arch/x86/include/asm/debugreg.h:88
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
In arch/x86/kernel/traps.c (ffffffff820bb961)
Location: arch/x86/include/asm/debugreg.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff820bc74f)
Location: arch/x86/include/asm/debugreg.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8105915e)
Location: arch/x86/include/asm/debugreg.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820be0c1)
Location: arch/x86/include/asm/debugreg.h:110
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
In arch/x86/kernel/traps.c (ffffffff8213d091)
Location: arch/x86/include/asm/debugreg.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8213dee9)
Location: arch/x86/include/asm/debugreg.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a70c)
Location: arch/x86/include/asm/debugreg.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213fb61)
Location: arch/x86/include/asm/debugreg.h:110
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
In arch/x86/kernel/traps.c (ffffffff8221f0b1)
Location: arch/x86/include/asm/debugreg.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8221fee5)
Location: arch/x86/include/asm/debugreg.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff810619e5)
Location: arch/x86/include/asm/debugreg.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221b81)
Location: arch/x86/include/asm/debugreg.h:111
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a1d6)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
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
In arch/x86/kernel/alternative.c (ffffffff81029a96)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
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
In arch/x86/kernel/alternative.c (ffffffff8103a036)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
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
In arch/x86/kernel/alternative.c (ffffffff8103b036)
Location: arch/x86/include/asm/debugreg.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
</details>
</li>
</ul>

## Differences
