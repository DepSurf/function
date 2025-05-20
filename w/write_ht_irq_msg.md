# Function: <code>write_ht_irq_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void write_ht_irq_msg(unsigned int irq, struct ht_irq_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/htirq.c (ffffffff81455630)
Location: drivers/pci/htirq.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_deactivate
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/pci/htirq.c:mask_ht_irq
  - drivers/pci/htirq.c:unmask_ht_irq
```
**Symbols:**

```
ffffffff81455630-ffffffff81455724: write_ht_irq_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void write_ht_irq_msg(unsigned int irq, struct ht_irq_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/htirq.c (ffffffff814a2260)
Location: drivers/pci/htirq.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_deactivate
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/pci/htirq.c:unmask_ht_irq
  - drivers/pci/htirq.c:mask_ht_irq
```
**Symbols:**

```
ffffffff814a2260-ffffffff814a2354: write_ht_irq_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void write_ht_irq_msg(unsigned int irq, struct ht_irq_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/htirq.c (ffffffff814c3eb0)
Location: drivers/pci/htirq.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_deactivate
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/pci/htirq.c:unmask_ht_irq
  - drivers/pci/htirq.c:mask_ht_irq
```
**Symbols:**

```
ffffffff814c3eb0-ffffffff814c3fa4: write_ht_irq_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void write_ht_irq_msg(unsigned int irq, struct ht_irq_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/htirq.c (ffffffff814ce180)
Location: drivers/pci/htirq.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_deactivate
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/pci/htirq.c:unmask_ht_irq
  - drivers/pci/htirq.c:mask_ht_irq
```
**Symbols:**

```
ffffffff814ce180-ffffffff814ce24f: write_ht_irq_msg (STB_GLOBAL)
```
</details>
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
</ul>
