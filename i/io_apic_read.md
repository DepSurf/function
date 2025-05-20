# Function: <code>io_apic_read</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81055d15)
Location: arch/x86/include/asm/io_apic.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105816d)
Location: arch/x86/include/asm/io_apic.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105aefd)
Location: arch/x86/include/asm/io_apic.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a4b3)
Location: arch/x86/include/asm/io_apic.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e9b9)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106196d)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106764d)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106adf3)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b793)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072c06)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81074066)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81074b16)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81081a87)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810915e3)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6287)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9468)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810b04f8)
Location: arch/x86/include/asm/io_apic.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b283)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b5bc)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b733)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ce33)
Location: arch/x86/include/asm/io_apic.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
  - arch/x86/kernel/apic/io_apic.c:__ioapic_read_entry
```
</details>
</li>
</ul>

## Differences
