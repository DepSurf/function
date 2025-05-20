# Function: <code>mp_save_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056dc0)
Location: arch/x86/kernel/apic/io_apic.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff81056dc0-ffffffff81056e9b: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057030)
Location: arch/x86/kernel/apic/io_apic.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
**Symbols:**

```
ffffffff81057030-ffffffff8105710b: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059de0)
Location: arch/x86/kernel/apic/io_apic.c:212
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
**Symbols:**

```
ffffffff81059de0-ffffffff81059ebb: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059450)
Location: arch/x86/kernel/apic/io_apic.c:212
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
**Symbols:**

```
ffffffff81059450-ffffffff81059504: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d940)
Location: arch/x86/kernel/apic/io_apic.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
```
**Symbols:**

```
ffffffff8105d940-ffffffff8105d9f4: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810620bd-ffffffff81062106: mp_save_irq.cold.21 (STB_LOCAL)
ffffffff81060aa0-ffffffff81060b19: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81067db2-ffffffff81067dfb: mp_save_irq.cold.19 (STB_LOCAL)
ffffffff81066780-ffffffff810667f9: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8106b54e-ffffffff8106b597: mp_save_irq.cold (STB_LOCAL)
ffffffff81069df0-ffffffff81069e69: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8106bede-ffffffff8106bf27: mp_save_irq.cold (STB_LOCAL)
ffffffff8106a790-ffffffff8106a809: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:smp_read_mpc
  - arch/x86/kernel/jailhouse.c:jailhouse_setup_irq
```
**Symbols:**

```
ffffffff810731fc-ffffffff81073245: mp_save_irq.cold (STB_LOCAL)
ffffffff81071b40-ffffffff81071bb9: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_setup_irq
```
**Symbols:**

```
ffffffff81bd7344-ffffffff81bd738d: mp_save_irq.cold (STB_LOCAL)
ffffffff81072ff0-ffffffff81073069: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_setup_irq
```
**Symbols:**

```
ffffffff81bc94f7-ffffffff81bc9540: mp_save_irq.cold (STB_LOCAL)
ffffffff81073ac0-ffffffff81073b39: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:202
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_setup_irq
```
**Symbols:**

```
ffffffff81c9e17b-ffffffff81c9e1c4: mp_save_irq.cold (STB_LOCAL)
ffffffff81080f60-ffffffff81081021: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:203
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_setup_irq
```
**Symbols:**

```
ffffffff81e4d61a-ffffffff81e4d663: mp_save_irq.cold (STB_LOCAL)
ffffffff810908f0-ffffffff81090a8b: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5420)
Location: arch/x86/kernel/apic/io_apic.c:203
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810a5420-ffffffff810a55d7: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8520)
Location: arch/x86/kernel/apic/io_apic.c:204
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810a8520-ffffffff810a878b: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af5b0)
Location: arch/x86/kernel/apic/io_apic.c:204
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810af5b0-ffffffff810af81b: mp_save_irq (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8106b9ce-ffffffff8106ba17: mp_save_irq.cold (STB_LOCAL)
ffffffff8106a280-ffffffff8106a2f9: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8105bcfe-ffffffff8105bd47: mp_save_irq.cold (STB_LOCAL)
ffffffff8105a5e0-ffffffff8105a659: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8106be7e-ffffffff8106bec7: mp_save_irq.cold (STB_LOCAL)
ffffffff8106a730-ffffffff8106a7a9: mp_save_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mp_save_irq(struct mpc_intsrc *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8106d57e-ffffffff8106d5c7: mp_save_irq.cold (STB_LOCAL)
ffffffff8106be30-ffffffff8106bea9: mp_save_irq (STB_GLOBAL)
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
