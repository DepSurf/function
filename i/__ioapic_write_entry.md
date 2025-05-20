# Function: <code>__ioapic_write_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055db3)
Location: arch/x86/kernel/apic/io_apic.c:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105645f)
Location: arch/x86/kernel/apic/io_apic.c:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105920f)
Location: arch/x86/kernel/apic/io_apic.c:332
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105886f)
Location: arch/x86/kernel/apic/io_apic.c:332
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105cf46)
Location: arch/x86/kernel/apic/io_apic.c:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ff06)
Location: arch/x86/kernel/apic/io_apic.c:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065c76)
Location: arch/x86/kernel/apic/io_apic.c:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106942f)
Location: arch/x86/kernel/apic/io_apic.c:335
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069daf)
Location: arch/x86/kernel/apic/io_apic.c:335
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810713ef)
Location: arch/x86/kernel/apic/io_apic.c:322
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff81070670-ffffffff810706d7: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072a14)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff81071b10-ffffffff81071b77: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073734)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff81072620-ffffffff81072687: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107fc58)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff8107e500-ffffffff8107e5c3: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108f50b)
Location: arch/x86/kernel/apic/io_apic.c:318
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff8108dbc0-ffffffff8108dc92: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a3feb)
Location: arch/x86/kernel/apic/io_apic.c:318
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff810a2360-ffffffff810a2432: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a70ab)
Location: arch/x86/kernel/apic/io_apic.c:319
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff810a5340-ffffffff810a5418: __ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ae0eb)
Location: arch/x86/kernel/apic/io_apic.c:319
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
```
**Symbols:**

```
ffffffff810ac3c0-ffffffff810ac498: __ioapic_write_entry (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106989f)
Location: arch/x86/kernel/apic/io_apic.c:335
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059bff)
Location: arch/x86/kernel/apic/io_apic.c:335
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069d4f)
Location: arch/x86/kernel/apic/io_apic.c:335
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b4cf)
Location: arch/x86/kernel/apic/io_apic.c:335
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
