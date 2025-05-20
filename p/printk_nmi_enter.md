# Function: <code>printk_nmi_enter</code>

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
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/nmi.c (ffffffff810df410)
Location: kernel/printk/nmi.c:260
Inline: False
```
**Symbols:**

```
ffffffff810df410-ffffffff810df427: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/nmi.c (ffffffff810e5a00)
Location: kernel/printk/nmi.c:283
Inline: False
```
**Symbols:**

```
ffffffff810e5a00-ffffffff810e5a17: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e4f50)
Location: kernel/printk/printk_safe.c:309
Inline: False
```
**Symbols:**

```
ffffffff810e4f50-ffffffff810e4f8b: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810ed1b0)
Location: kernel/printk/printk_safe.c:306
Inline: False
```
**Symbols:**

```
ffffffff810ed1b0-ffffffff810ed1eb: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810f5450)
Location: kernel/printk/printk_safe.c:309
Inline: False
```
**Symbols:**

```
ffffffff810f5450-ffffffff810f5461: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81100bf0)
Location: kernel/printk/printk_safe.c:309
Inline: False
```
**Symbols:**

```
ffffffff81100bf0-ffffffff81100c01: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811093b0)
Location: kernel/printk/printk_safe.c:297
Inline: False
```
**Symbols:**

```
ffffffff811093b0-ffffffff811093bc: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81115780)
Location: kernel/printk/printk_safe.c:297
Inline: False
```
**Symbols:**

```
ffffffff81115780-ffffffff8111578c: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81bbf830)
Location: kernel/printk/printk_safe.c:298
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
**Symbols:**

```
ffffffff81bbf830-ffffffff81bbf83c: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81c38610)
Location: kernel/printk/printk_safe.c:306
Inline: False
Direct callers:
  - kernel/entry/common.c:irqentry_nmi_enter
```
**Symbols:**

```
ffffffff81c38610-ffffffff81c3861c: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81c2aa20)
Location: kernel/printk/printk_safe.c:298
Inline: False
Direct callers:
  - kernel/entry/common.c:irqentry_nmi_enter
```
**Symbols:**

```
ffffffff81c2aa20-ffffffff81c2aa2c: printk_nmi_enter (STB_GLOBAL)
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
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010176e68)
Location: kernel/printk/printk_safe.c:297
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
**Symbols:**

```
ffff800010176e68-ffff800010176e90: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c8be0)
Location: kernel/printk/printk_safe.c:297
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/smp.c:handle_IPI
```
**Symbols:**

```
c03c8be0-c03c8c14: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d06e0)
Location: kernel/printk/printk_safe.c:297
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
```
**Symbols:**

```
c0000000001d06e0-c0000000001d0730: printk_nmi_enter (STB_GLOBAL)
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
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110dd60)
Location: kernel/printk/printk_safe.c:297
Inline: False
```
**Symbols:**

```
ffffffff8110dd60-ffffffff8110dd6c: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810feac0)
Location: kernel/printk/printk_safe.c:297
Inline: False
```
**Symbols:**

```
ffffffff810feac0-ffffffff810feacc: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110bc50)
Location: kernel/printk/printk_safe.c:297
Inline: False
```
**Symbols:**

```
ffffffff8110bc50-ffffffff8110bc5c: printk_nmi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void printk_nmi_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81117160)
Location: kernel/printk/printk_safe.c:297
Inline: False
```
**Symbols:**

```
ffffffff81117160-ffffffff8111716c: printk_nmi_enter (STB_GLOBAL)
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
