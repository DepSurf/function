# Function: <code>ioapic_read_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055d40)
Location: arch/x86/kernel/apic/io_apic.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff81055d40-ffffffff81055d88: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055f90)
Location: arch/x86/kernel/apic/io_apic.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81055f90-ffffffff81055fd8: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058d40)
Location: arch/x86/kernel/apic/io_apic.c:314
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81058d40-ffffffff81058d88: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058390)
Location: arch/x86/kernel/apic/io_apic.c:314
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81058390-ffffffff810583d8: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105c8a0)
Location: arch/x86/kernel/apic/io_apic.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff8105c8a0-ffffffff8105c8e8: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105f910)
Location: arch/x86/kernel/apic/io_apic.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff8105f910-ffffffff8105f958: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065580)
Location: arch/x86/kernel/apic/io_apic.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81065580-ffffffff810655c8: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81068ca0)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81068ca0-ffffffff81068cec: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069620)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81069620-ffffffff8106966c: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107128f)
Location: arch/x86/kernel/apic/io_apic.c:304
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
```
**Symbols:**

```
ffffffff81070620-ffffffff8107066c: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107269f)
Location: arch/x86/kernel/apic/io_apic.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
```
**Symbols:**

```
ffffffff81071ac0-ffffffff81071b0c: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107316f)
Location: arch/x86/kernel/apic/io_apic.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
```
**Symbols:**

```
ffffffff810725d0-ffffffff8107261c: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f4c1)
Location: arch/x86/kernel/apic/io_apic.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
```
**Symbols:**

```
ffffffff8107e4b0-ffffffff8107e4fc: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108f022)
Location: arch/x86/kernel/apic/io_apic.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
```
**Symbols:**

```
ffffffff8108db70-ffffffff8108dbc0: ioapic_read_entry (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f078)
Location: arch/x86/kernel/apic/io_apic.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
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
In arch/x86/kernel/apic/io_apic.c (ffffffff836b2918)
Location: arch/x86/kernel/apic/io_apic.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
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
In arch/x86/kernel/apic/io_apic.c (ffffffff838e31f8)
Location: arch/x86/kernel/apic/io_apic.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
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
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069110)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81069110-ffffffff8106915c: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059470)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff81059470-ffffffff810594bc: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810695c0)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff810695c0-ffffffff8106960c: ioapic_read_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct IO_APIC_route_entry ioapic_read_entry(int apic, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106acc0)
Location: arch/x86/kernel/apic/io_apic.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:io_apic_print_entries
  - arch/x86/kernel/apic/io_apic.c:save_ioapic_entries
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
```
**Symbols:**

```
ffffffff8106acc0-ffffffff8106ad0c: ioapic_read_entry (STB_LOCAL)
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
