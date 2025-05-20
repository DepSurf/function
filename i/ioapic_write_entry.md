# Function: <code>ioapic_write_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055d90)
Location: arch/x86/kernel/apic/io_apic.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
```
**Symbols:**

```
ffffffff81055d90-ffffffff81055e29: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055fe0)
Location: arch/x86/kernel/apic/io_apic.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81055fe0-ffffffff81056079: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058d90)
Location: arch/x86/kernel/apic/io_apic.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81058d90-ffffffff81058e29: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810583e0)
Location: arch/x86/kernel/apic/io_apic.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff810583e0-ffffffff81058479: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105c8f0)
Location: arch/x86/kernel/apic/io_apic.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff8105c8f0-ffffffff8105c989: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105f960)
Location: arch/x86/kernel/apic/io_apic.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff8105f960-ffffffff8105f9f9: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810655d0)
Location: arch/x86/kernel/apic/io_apic.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff810655d0-ffffffff81065669: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81068cf0)
Location: arch/x86/kernel/apic/io_apic.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81068cf0-ffffffff81068d88: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069670)
Location: arch/x86/kernel/apic/io_apic.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81069670-ffffffff81069708: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071fef)
Location: arch/x86/kernel/apic/io_apic.c:331
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
```
**Symbols:**

```
ffffffff810706e0-ffffffff81070730: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810734b0)
Location: arch/x86/kernel/apic/io_apic.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
```
**Symbols:**

```
ffffffff81071b80-ffffffff81071bd0: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073f80)
Location: arch/x86/kernel/apic/io_apic.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
```
**Symbols:**

```
ffffffff81072690-ffffffff810726e0: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810817a0)
Location: arch/x86/kernel/apic/io_apic.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
```
**Symbols:**

```
ffffffff8107e5d0-ffffffff8107e620: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81091298)
Location: arch/x86/kernel/apic/io_apic.c:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
```
**Symbols:**

```
ffffffff8108dca0-ffffffff8108dcfa: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f0f5)
Location: arch/x86/kernel/apic/io_apic.c:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b2995)
Location: arch/x86/kernel/apic/io_apic.c:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e328c)
Location: arch/x86/kernel/apic/io_apic.c:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
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
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069160)
Location: arch/x86/kernel/apic/io_apic.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81069160-ffffffff810691f8: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810594c0)
Location: arch/x86/kernel/apic/io_apic.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff810594c0-ffffffff81059558: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069610)
Location: arch/x86/kernel/apic/io_apic.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81069610-ffffffff810696a8: ioapic_write_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioapic_write_entry(int apic, int pin, struct IO_APIC_route_entry e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ad10)
Location: arch/x86/kernel/apic/io_apic.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
  - arch/x86/kernel/apic/io_apic.c:restore_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff8106ad10-ffffffff8106ada8: ioapic_write_entry (STB_LOCAL)
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
