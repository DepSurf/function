# Function: <code>irq_domain_deactivate_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e1890)
Location: kernel/irq/irqdomain.c:1318
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
**Symbols:**

```
ffffffff810e1890-ffffffff810e18d2: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e7330)
Location: kernel/irq/irqdomain.c:1376
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
**Symbols:**

```
ffffffff810e7330-ffffffff810e7372: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810edd00)
Location: kernel/irq/irqdomain.c:1422
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - kernel/irq/chip.c:irq_shutdown
```
**Symbols:**

```
ffffffff810edd00-ffffffff810edd2b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed6b0)
Location: kernel/irq/irqdomain.c:1562
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_shutdown
```
**Symbols:**

```
ffffffff810ed6b0-ffffffff810ed6dc: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f60e0)
Location: kernel/irq/irqdomain.c:1744
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810f60e0-ffffffff810f610c: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fe450)
Location: kernel/irq/irqdomain.c:1628
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810fe450-ffffffff810fe47b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109c20)
Location: kernel/irq/irqdomain.c:1628
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/chip.c:irq_shutdown
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81109c20-ffffffff81109c4b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811131f0)
Location: kernel/irq/irqdomain.c:1665
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff811131f0-ffffffff8111321b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f490)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8111f490-ffffffff8111f4bb: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b9d0)
Location: kernel/irq/irqdomain.c:1670
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8112b9d0-ffffffff8112b9fe: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127490)
Location: kernel/irq/irqdomain.c:1792
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81127490-ffffffff811274be: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127750)
Location: kernel/irq/irqdomain.c:1755
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:__msi_domain_free_irqs
```
**Symbols:**

```
ffffffff81127750-ffffffff8112777e: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81147cc0)
Location: kernel/irq/irqdomain.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:__msi_domain_free_irqs
```
**Symbols:**

```
ffffffff81147cc0-ffffffff81147cee: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116c180)
Location: kernel/irq/irqdomain.c:1804
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:__msi_domain_free_irqs
```
**Symbols:**

```
ffffffff8116c180-ffffffff8116c1be: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a10c0)
Location: kernel/irq/irqdomain.c:1872
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff811a10c0-ffffffff811a10fe: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2f20)
Location: kernel/irq/irqdomain.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff811b2f20-ffffffff811b2f5e: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2d40)
Location: kernel/irq/irqdomain.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff811c2d40-ffffffff811c2d7e: irq_domain_deactivate_irq (STB_GLOBAL)
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
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010185108)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffff800010185108-ffff80001018515c: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d41d4)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
c03d41d4-c03d4214: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d4a4c)
Location: kernel/irq/internals.h:462
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/irq/chip.c (c0000000001d99f4)
Location: kernel/irq/internals.h:462
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011be94)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffe00011be94-ffffffe00011bedc: irq_domain_deactivate_irq (STB_GLOBAL)
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
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81117a70)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81117a70-ffffffff81117a9b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108760)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81108760-ffffffff8110878b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115960)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81115960-ffffffff8111598b: irq_domain_deactivate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120f90)
Location: kernel/irq/irqdomain.c:1668
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81120f90-ffffffff81120fbb: irq_domain_deactivate_irq (STB_GLOBAL)
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
