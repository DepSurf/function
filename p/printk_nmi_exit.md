# Function: <code>printk_nmi_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/nmi.c (ffffffff810df430)
Location: kernel/printk/nmi.c:265
Inline: False
```
**Symbols:**

```
ffffffff810df430-ffffffff810df447: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/nmi.c (ffffffff810e5a20)
Location: kernel/printk/nmi.c:288
Inline: False
```
**Symbols:**

```
ffffffff810e5a20-ffffffff810e5a37: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e4f90)
Location: kernel/printk/printk_safe.c:324
Inline: False
```
**Symbols:**

```
ffffffff810e4f90-ffffffff810e4fa6: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810ed1f0)
Location: kernel/printk/printk_safe.c:321
Inline: False
```
**Symbols:**

```
ffffffff810ed1f0-ffffffff810ed206: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810f5470)
Location: kernel/printk/printk_safe.c:314
Inline: False
```
**Symbols:**

```
ffffffff810f5470-ffffffff810f5481: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81100c10)
Location: kernel/printk/printk_safe.c:314
Inline: False
```
**Symbols:**

```
ffffffff81100c10-ffffffff81100c21: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811093c0)
Location: kernel/printk/printk_safe.c:302
Inline: False
```
**Symbols:**

```
ffffffff811093c0-ffffffff811093cc: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81115790)
Location: kernel/printk/printk_safe.c:302
Inline: False
```
**Symbols:**

```
ffffffff81115790-ffffffff8111579c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81bbf840)
Location: kernel/printk/printk_safe.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
**Symbols:**

```
ffffffff81bbf840-ffffffff81bbf84c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81c38620)
Location: kernel/printk/printk_safe.c:311
Inline: False
Direct callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
**Symbols:**

```
ffffffff81c38620-ffffffff81c3862c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81c2aa30)
Location: kernel/printk/printk_safe.c:303
Inline: False
Direct callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
**Symbols:**

```
ffffffff81c2aa30-ffffffff81c2aa3c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010176e90)
Location: kernel/printk/printk_safe.c:302
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
**Symbols:**

```
ffff800010176e90-ffff800010176eb8: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c8c14)
Location: kernel/printk/printk_safe.c:302
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/smp.c:handle_IPI
```
**Symbols:**

```
c03c8c14-c03c8c48: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d0730)
Location: kernel/printk/printk_safe.c:302
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
```
**Symbols:**

```
c0000000001d0730-c0000000001d0780: printk_nmi_exit (STB_GLOBAL)
```
</details>
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
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110dd70)
Location: kernel/printk/printk_safe.c:302
Inline: False
```
**Symbols:**

```
ffffffff8110dd70-ffffffff8110dd7c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810fead0)
Location: kernel/printk/printk_safe.c:302
Inline: False
```
**Symbols:**

```
ffffffff810fead0-ffffffff810feadc: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110bc60)
Location: kernel/printk/printk_safe.c:302
Inline: False
```
**Symbols:**

```
ffffffff8110bc60-ffffffff8110bc6c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void printk_nmi_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81117170)
Location: kernel/printk/printk_safe.c:302
Inline: False
```
**Symbols:**

```
ffffffff81117170-ffffffff8111717c: printk_nmi_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
