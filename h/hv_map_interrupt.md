# Function: <code>hv_map_interrupt</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/hyperv/irqdomain.c:15
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81033400-ffffffff810336d4: hv_map_interrupt (STB_LOCAL)
ffffffff81bc52d7-ffffffff81bc530f: hv_map_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/hyperv/irqdomain.c:15
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81038590-ffffffff81038887: hv_map_interrupt (STB_LOCAL)
ffffffff81c97e86-ffffffff81c97edf: hv_map_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/hyperv/irqdomain.c:15
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff8103e820-ffffffff8103eb3b: hv_map_interrupt (STB_LOCAL)
ffffffff81e472c9-ffffffff81e4731a: hv_map_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047890)
Location: arch/x86/hyperv/irqdomain.c:15
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81047890-ffffffff81047b17: hv_map_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/hyperv/irqdomain.c:15
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81047ab0-ffffffff81047e0a: hv_map_interrupt (STB_LOCAL)
ffffffff820d03ee-ffffffff820d042a: hv_map_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/hyperv/irqdomain.c:15
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff8104e210-ffffffff8104e4f0: hv_map_interrupt (STB_LOCAL)
ffffffff821aae02-ffffffff821aae3f: hv_map_interrupt.cold (STB_LOCAL)
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
