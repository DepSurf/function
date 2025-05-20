# Function: <code>irq_move_masked_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810e25a0)
Location: kernel/irq/migration.c:7
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_irq
```
**Symbols:**

```
ffffffff810e25a0-ffffffff810e2674: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810e8030)
Location: kernel/irq/migration.c:7
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff810e8030-ffffffff810e8104: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810eea70)
Location: kernel/irq/migration.c:7
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff810eea70-ffffffff810eeb47: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810ee5b0)
Location: kernel/irq/migration.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff810ee5b0-ffffffff810ee676: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810f6fe0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff810f6fe0-ffffffff810f70a6: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810ff310)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff810ff310-ffffffff810ff3e8: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff8110aaf0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff8110aaf0-ffffffff8110abc8: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/migration.c (0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff811142e2-ffffffff811142f5: irq_move_masked_irq.cold (STB_LOCAL)
ffffffff811141a0-ffffffff8111427e: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff81120310)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff81120310-ffffffff811203ee: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff8112c850)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff8112c850-ffffffff8112c92e: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff81128280)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff81128280-ffffffff8112835e: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff81128540)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff81128540-ffffffff81128620: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff81148b10)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff81148b10-ffffffff81148bf0: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff8116d640)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff8116d640-ffffffff8116d72c: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff811a27e0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff811a27e0-ffffffff811a28cc: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff811b46e0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff811b46e0-ffffffff811b47cc: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff811c4560)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff811c4560-ffffffff811c464c: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: include/linux/irq.h:592
Inline: True
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff811188f0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff811188f0-ffffffff811189ce: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff81109960)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
```
**Symbols:**

```
ffffffff81109960-ffffffff81109a3e: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff811167e0)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff811167e0-ffffffff811168be: irq_move_masked_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_move_masked_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff81121e20)
Location: kernel/irq/migration.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:__irq_move_irq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffffffff81121e20-ffffffff81121efe: irq_move_masked_irq (STB_GLOBAL)
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
