# Function: <code>mp_register_ioapic_irq</code>

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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff826b88e7)
Location: arch/x86/kernel/acpi/boot.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff826b88e7-ffffffff826b899e: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff826e282e)
Location: arch/x86/kernel/acpi/boot.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff826e282e-ffffffff826e28e5: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8289907a)
Location: arch/x86/kernel/acpi/boot.c:423
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff8289907a-ffffffff82899131: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b0d5a)
Location: arch/x86/kernel/acpi/boot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff828b0d5a-ffffffff828b0e12: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b41a7)
Location: arch/x86/kernel/acpi/boot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff828b41a7-ffffffff828b425f: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9589)
Location: arch/x86/kernel/acpi/boot.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff82cd9589-ffffffff82cd9641: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc5ade)
Location: arch/x86/kernel/acpi/boot.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff82fc5ade-ffffffff82fc5b96: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff831d0207)
Location: arch/x86/kernel/acpi/boot.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff831d0207-ffffffff831d02bf: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff832b255e)
Location: arch/x86/kernel/acpi/boot.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff832b255e-ffffffff832b2616: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff834639a8)
Location: arch/x86/kernel/acpi/boot.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff834639a8-ffffffff83463a7a: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff83e86550)
Location: arch/x86/kernel/acpi/boot.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff83e86550-ffffffff83e86622: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff836a9aa0)
Location: arch/x86/kernel/acpi/boot.c:492
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff836a9aa0-ffffffff836a9b70: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff838da240)
Location: arch/x86/kernel/acpi/boot.c:501
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff838da240-ffffffff838da310: mp_register_ioapic_irq (STB_LOCAL)
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828a21c6)
Location: arch/x86/kernel/acpi/boot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff828a21c6-ffffffff828a227e: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8289a308)
Location: arch/x86/kernel/acpi/boot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff8289a308-ffffffff8289a3c0: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b50c3)
Location: arch/x86/kernel/acpi/boot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff828b50c3-ffffffff828b517b: mp_register_ioapic_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b51aa)
Location: arch/x86/kernel/acpi/boot.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
```
**Symbols:**

```
ffffffff828b51aa-ffffffff828b5262: mp_register_ioapic_irq (STB_LOCAL)
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
