# Function: <code>io_apic_write</code>

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
Location: arch/x86/kernel/apic/io_apic.c:291
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105646c)
Location: arch/x86/kernel/apic/io_apic.c:291
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105921c)
Location: arch/x86/kernel/apic/io_apic.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105887c)
Location: arch/x86/kernel/apic/io_apic.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ecde)
Location: arch/x86/kernel/apic/io_apic.c:291
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81061c20)
Location: arch/x86/kernel/apic/io_apic.c:292
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81067900)
Location: arch/x86/kernel/apic/io_apic.c:292
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b0bb)
Location: arch/x86/kernel/apic/io_apic.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ba5b)
Location: arch/x86/kernel/apic/io_apic.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81071712)
Location: arch/x86/kernel/apic/io_apic.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072d42)
Location: arch/x86/kernel/apic/io_apic.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81073479)
Location: arch/x86/kernel/apic/io_apic.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f903)
Location: arch/x86/kernel/apic/io_apic.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ed8f)
Location: arch/x86/kernel/apic/io_apic.c:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a35d6)
Location: arch/x86/kernel/apic/io_apic.c:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6569)
Location: arch/x86/kernel/apic/io_apic.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810ad5c9)
Location: arch/x86/kernel/apic/io_apic.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b54b)
Location: arch/x86/kernel/apic/io_apic.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b87d)
Location: arch/x86/kernel/apic/io_apic.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b9fb)
Location: arch/x86/kernel/apic/io_apic.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106d0fb)
Location: arch/x86/kernel/apic/io_apic.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
```
</details>
</li>
</ul>

## Differences
