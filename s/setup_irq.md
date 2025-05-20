# Function: <code>setup_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dcc80)
Location: kernel/irq/manage.c:1413
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff810dcc80-ffffffff810dcd13: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e2390)
Location: kernel/irq/manage.c:1434
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff810e2390-ffffffff810e245b: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8cb0)
Location: kernel/irq/manage.c:1434
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff810e8cb0-ffffffff810e8d78: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8250)
Location: kernel/irq/manage.c:1450
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff810e8250-ffffffff810e82d9: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f0620)
Location: kernel/irq/manage.c:1503
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff810f0620-ffffffff810f06a9: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f89e0)
Location: kernel/irq/manage.c:1547
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff810f89e0-ffffffff810f8a69: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81104180)
Location: kernel/irq/manage.c:1560
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff81104180-ffffffff81104209: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1668
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff8110d882-ffffffff8110d89b: setup_irq.cold (STB_LOCAL)
ffffffff8110cc70-ffffffff8110ccf3: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119050)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff81119050-ffffffff811190d9: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017baf0)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - drivers/clocksource/timer-sp804.c:__sp804_clockevents_init
```
**Symbols:**

```
ffff80001017baf0-ffff80001017bba4: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ccbf0)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/plat-omap/dma.c:omap_system_dma_probe
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_init
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/timer-sp804.c:__sp804_clockevents_init
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
```
**Symbols:**

```
c03ccbf0-c03ccc90: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d6440)
Location: kernel/irq/manage.c:1660
Inline: False
```
**Symbols:**

```
c0000000001d6440-c0000000001d654c: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000115450)
Location: kernel/irq/manage.c:1660
Inline: False
```
**Symbols:**

```
ffffffe000115450-ffffffe0001154d8: setup_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81111630)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff81111630-ffffffff811116b9: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102360)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff81102360-ffffffff811023e9: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f520)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff8110f520-ffffffff8110f5a9: setup_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int setup_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111aa50)
Location: kernel/irq/manage.c:1660
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
**Symbols:**

```
ffffffff8111aa50-ffffffff8111aad9: setup_irq (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
