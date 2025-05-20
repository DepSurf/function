# Function: <code>irq_domain_activate_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_activate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e1840)
Location: kernel/irq/irqdomain.c:1298
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_resume
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
```
**Symbols:**

```
ffffffff810e1840-ffffffff810e1887: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_activate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e72e0)
Location: kernel/irq/irqdomain.c:1356
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_resume
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/irqdomain.c:irq_domain_activate_irq
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810e72e0-ffffffff810e7327: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_activate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810edcd0)
Location: kernel/irq/irqdomain.c:1406
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810edcd0-ffffffff810edcfb: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_activate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed680)
Location: kernel/irq/irqdomain.c:1546
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:__irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810ed680-ffffffff810ed6ac: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f60a0)
Location: kernel/irq/irqdomain.c:1725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810f60a0-ffffffff810f60dd: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fe410)
Location: kernel/irq/irqdomain.c:1609
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810fe410-ffffffff810fe44d: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109be0)
Location: kernel/irq/irqdomain.c:1609
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81109be0-ffffffff81109c1d: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811131b0)
Location: kernel/irq/irqdomain.c:1646
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff811131b0-ffffffff811131ed: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f450)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8111f450-ffffffff8111f48d: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b990)
Location: kernel/irq/irqdomain.c:1651
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:__irq_startup_managed
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8112b990-ffffffff8112b9d0: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127450)
Location: kernel/irq/irqdomain.c:1773
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:__irq_startup_managed
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81127450-ffffffff81127490: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127710)
Location: kernel/irq/irqdomain.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81127710-ffffffff81127750: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81147c80)
Location: kernel/irq/irqdomain.c:1781
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81147c80-ffffffff81147cc0: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116c120)
Location: kernel/irq/irqdomain.c:1785
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8116c120-ffffffff8116c174: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a1050)
Location: kernel/irq/irqdomain.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff811a1050-ffffffff811a10a4: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2eb0)
Location: kernel/irq/irqdomain.c:1834
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff811b2eb0-ffffffff811b2f04: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2cd0)
Location: kernel/irq/irqdomain.c:1834
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff811c2cd0-ffffffff811c2d24: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101850a8)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffff8000101850a8-ffff800010185104: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d4184)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
c03d4184-c03d41d4: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9d60)
Location: kernel/irq/internals.h:457
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011be48)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffe00011be48-ffffffe00011be94: irq_domain_activate_irq (STB_GLOBAL)
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
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81117a30)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81117a30-ffffffff81117a6d: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108720)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81108720-ffffffff8110875d: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115920)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81115920-ffffffff8111595d: irq_domain_activate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120f50)
Location: kernel/irq/irqdomain.c:1649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81120f50-ffffffff81120f8d: irq_domain_activate_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reserve</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
