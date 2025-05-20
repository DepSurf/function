# Function: <code>mpc_ioapic_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055db3)
Location: arch/x86/kernel/apic/io_apic.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
**Symbols:**

```
ffffffff81056d70-ffffffff81056d89: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056472)
Location: arch/x86/kernel/apic/io_apic.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81056fe0-ffffffff81056ff9: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059222)
Location: arch/x86/kernel/apic/io_apic.c:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81059d90-ffffffff81059da9: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058882)
Location: arch/x86/kernel/apic/io_apic.c:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_activate
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81059400-ffffffff81059419: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ecde)
Location: arch/x86/kernel/apic/io_apic.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff8105d8f0-ffffffff8105d909: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81061ce2)
Location: arch/x86/kernel/apic/io_apic.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81060a50-ffffffff81060a69: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810679c2)
Location: arch/x86/kernel/apic/io_apic.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81066730-ffffffff81066749: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b6fe)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81069da0-ffffffff81069db9: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106c062)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff8106a740-ffffffff8106a759: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810733f5)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81071af0-ffffffff81071b09: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81bd752a)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81072fa0-ffffffff81072fb9: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81bc96c8)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81073a70-ffffffff81073a89: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81081cad)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81080ef0-ffffffff81080f25: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81091819)
Location: arch/x86/kernel/apic/io_apic.c:131
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff81090880-ffffffff810908bd: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a65a2)
Location: arch/x86/kernel/apic/io_apic.c:131
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff810a5390-ffffffff810a53cd: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9795)
Location: arch/x86/kernel/apic/io_apic.c:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff810a8490-ffffffff810a84d0: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810b0825)
Location: arch/x86/kernel/apic/io_apic.c:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:eoi_ioapic_pin
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff810af520-ffffffff810af560: mpc_ioapic_addr (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bb52)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff8106a230-ffffffff8106a249: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105be7b)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff8105a590-ffffffff8105a5a9: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106c002)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff8106a6e0-ffffffff8106a6f9: mpc_ioapic_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int mpc_ioapic_addr(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106d702)
Location: arch/x86/kernel/apic/io_apic.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:io_apic_sync
  - arch/x86/kernel/apic/io_apic.c:io_apic_modify_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_mask_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_write_entry
  - arch/x86/kernel/apic/io_apic.c:native_io_apic_read
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff8106bde0-ffffffff8106bdf9: mpc_ioapic_addr (STB_GLOBAL)
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
