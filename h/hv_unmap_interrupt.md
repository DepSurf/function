# Function: <code>hv_unmap_interrupt</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry *old_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81033170)
Location: arch/x86/hyperv/irqdomain.c:72
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81033170-ffffffff81033241: hv_unmap_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry *old_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81038310)
Location: arch/x86/hyperv/irqdomain.c:72
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81038310-ffffffff810383e1: hv_unmap_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry *old_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e600)
Location: arch/x86/hyperv/irqdomain.c:72
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff8103e600-ffffffff8103e6d3: hv_unmap_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry *old_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810474f0)
Location: arch/x86/hyperv/irqdomain.c:72
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff810474f0-ffffffff810475cc: hv_unmap_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry *old_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047870)
Location: arch/x86/hyperv/irqdomain.c:72
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81047870-ffffffff8104794c: hv_unmap_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry *old_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e120)
Location: arch/x86/hyperv/irqdomain.c:72
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff8104e120-ffffffff8104e1b4: hv_unmap_interrupt (STB_LOCAL)
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
