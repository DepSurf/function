# Function: <code>mp_map_pin_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057490)
Location: arch/x86/kernel/apic/io_apic.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81057490-ffffffff81057783: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057740)
Location: arch/x86/kernel/apic/io_apic.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff81057740-ffffffff81057a48: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a4d0)
Location: arch/x86/kernel/apic/io_apic.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8105a4d0-ffffffff8105a7d8: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059b00)
Location: arch/x86/kernel/apic/io_apic.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff81059b00-ffffffff81059de4: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105dff0)
Location: arch/x86/kernel/apic/io_apic.c:1030
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8105dff0-ffffffff8105e2d6: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81061030)
Location: arch/x86/kernel/apic/io_apic.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff81061030-ffffffff810612fd: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81066d10)
Location: arch/x86/kernel/apic/io_apic.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff81066d10-ffffffff81066fd3: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a4d0)
Location: arch/x86/kernel/apic/io_apic.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8106a4d0-ffffffff8106a79f: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ae70)
Location: arch/x86/kernel/apic/io_apic.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8106ae70-ffffffff8106b13f: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072250)
Location: arch/x86/kernel/apic/io_apic.c:1021
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81072250-ffffffff81072527: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073730)
Location: arch/x86/kernel/apic/io_apic.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81073730-ffffffff81073a2b: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81074200)
Location: arch/x86/kernel/apic/io_apic.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81074200-ffffffff81074513: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8107ff70-ffffffff81080389: mp_map_pin_to_irq (STB_LOCAL)
ffffffff81c9e033-ffffffff81c9e069: mp_map_pin_to_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1021
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8108f850-ffffffff8108fcad: mp_map_pin_to_irq (STB_LOCAL)
ffffffff81e4d4f3-ffffffff81e4d529: mp_map_pin_to_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1021
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff810a4380-ffffffff810a480b: mp_map_pin_to_irq (STB_LOCAL)
ffffffff82053d33-ffffffff82053d69: mp_map_pin_to_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1022
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff810a7440-ffffffff810a78e4: mp_map_pin_to_irq (STB_LOCAL)
ffffffff820d2355-ffffffff820d238b: mp_map_pin_to_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1022
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff810ae4a0-ffffffff810ae944: mp_map_pin_to_irq (STB_LOCAL)
ffffffff821ad073-ffffffff821ad0a9: mp_map_pin_to_irq.cold (STB_LOCAL)
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
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a960)
Location: arch/x86/kernel/apic/io_apic.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8106a960-ffffffff8106ac2f: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105acc0)
Location: arch/x86/kernel/apic/io_apic.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8105acc0-ffffffff8105af8f: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ae10)
Location: arch/x86/kernel/apic/io_apic.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8106ae10-ffffffff8106b0df: mp_map_pin_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mp_map_pin_to_irq(u32 gsi, int idx, int ioapic, int pin, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106c510)
Location: arch/x86/kernel/apic/io_apic.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:pin_2_irq
```
**Symbols:**

```
ffffffff8106c510-ffffffff8106c7df: mp_map_pin_to_irq (STB_LOCAL)
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
