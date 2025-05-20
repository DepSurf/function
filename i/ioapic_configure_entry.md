# Function: <code>ioapic_configure_entry</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105cf10)
Location: arch/x86/kernel/apic/io_apic.c:1866
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff8105cf10-ffffffff8105cfba: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105fed0)
Location: arch/x86/kernel/apic/io_apic.c:1859
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff8105fed0-ffffffff8105ff7a: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065c40)
Location: arch/x86/kernel/apic/io_apic.c:1859
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff81065c40-ffffffff81065cea: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069400)
Location: arch/x86/kernel/apic/io_apic.c:1862
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff81069400-ffffffff810694a7: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069d80)
Location: arch/x86/kernel/apic/io_apic.c:1865
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff81069d80-ffffffff81069e27: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810713c0)
Location: arch/x86/kernel/apic/io_apic.c:1852
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff810713c0-ffffffff81071467: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810729a0)
Location: arch/x86/kernel/apic/io_apic.c:1908
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff810729a0-ffffffff81072a91: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810736c0)
Location: arch/x86/kernel/apic/io_apic.c:1908
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff810736c0-ffffffff810737b1: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107fbc0)
Location: arch/x86/kernel/apic/io_apic.c:1908
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff8107fbc0-ffffffff8107fd24: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108f460)
Location: arch/x86/kernel/apic/io_apic.c:1909
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff8108f460-ffffffff8108f5f4: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a3f40)
Location: arch/x86/kernel/apic/io_apic.c:1909
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff810a3f40-ffffffff810a40d4: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a7000)
Location: arch/x86/kernel/apic/io_apic.c:1910
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff810a7000-ffffffff810a719a: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ae040)
Location: arch/x86/kernel/apic/io_apic.c:1906
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff810ae040-ffffffff810ae1da: ioapic_configure_entry (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069870)
Location: arch/x86/kernel/apic/io_apic.c:1871
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff81069870-ffffffff81069917: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059bd0)
Location: arch/x86/kernel/apic/io_apic.c:1865
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff81059bd0-ffffffff81059c77: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069d20)
Location: arch/x86/kernel/apic/io_apic.c:1865
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff81069d20-ffffffff81069dc7: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioapic_configure_entry(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b4a0)
Location: arch/x86/kernel/apic/io_apic.c:1865
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
**Symbols:**

```
ffffffff8106b4a0-ffffffff8106b547: ioapic_configure_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
