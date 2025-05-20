# Function: <code>irq_bypass_register_producer</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81aad0d0)
Location: virt/lib/irqbypass.c:84
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81aad0d0-ffffffff81aad1e9: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bb4540)
Location: virt/lib/irqbypass.c:84
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81bb4540-ffffffff81bb4643: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bc97a0)
Location: virt/lib/irqbypass.c:88
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81bc97a0-ffffffff81bc98a3: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bbd0d0)
Location: virt/lib/irqbypass.c:84
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81bbd0d0-ffffffff81bbd1d3: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81c8cfc0)
Location: virt/lib/irqbypass.c:84
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81c8cfc0-ffffffff81c8d0c3: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81e3bdf0)
Location: virt/lib/irqbypass.c:84
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81e3bdf0-ffffffff81e3bf0e: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffff800010d81a90)
Location: virt/lib/irqbypass.c:84
Inline: True
```
**Symbols:**

```
ffff800010d81a90-ffff800010d81bcc: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (c000000000ec1b80)
Location: virt/lib/irqbypass.c:84
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
c000000000ec1b80-c000000000ec1d0c: irq_bypass_register_producer (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81a09050)
Location: virt/lib/irqbypass.c:84
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81a09050-ffffffff81a09169: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ab8310)
Location: virt/lib/irqbypass.c:84
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81ab8310-ffffffff81ab8429: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_producer(struct irq_bypass_producer *producer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ac4730)
Location: virt/lib/irqbypass.c:84
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81ac4730-ffffffff81ac4844: irq_bypass_register_producer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
