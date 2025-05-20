# Function: <code>acpi_os_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8181ad98)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/nvs.c (ffffffff8147b4d5)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c87a4)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff814c9ae0)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/mailbox/pcc.c (ffffffff81fe54ef)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea6e8)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff814eba24)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525b0c)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff82023c97)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6500)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff814f7d63)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81538815)
Location: include/acpi/acpi_io.h:9
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff82106d2e)
Location: include/acpi/acpi_io.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536cb0)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81539113)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159a0c9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff82710683)
Location: include/acpi/acpi_io.h:10
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c8c9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff8156ef2e)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d19c6)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8273a904)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815844f9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81586aee)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815eafe6)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff828f48ff)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b50fb)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff815b77a2)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161cd84)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff82910244)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d632b)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff815d89d2)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163e831)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff82919f5c)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8168002b)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff816828c3)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb9b0)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff82d2c3e8)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:pcc_parse_subspace_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169eb07)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81c00c4f)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170900f)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8301adf4)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:pcc_parse_subspace_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816817b9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81bf2678)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ea62e)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff83225e9d)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f68a9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81ceefad)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817640c5)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff833100dc)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff818236fc)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81eb6724)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81843086)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81898052)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81bca91e)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8195495c)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff81957a90)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/acpi_pcc.c (ffffffff8197a265)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e033d)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81d73ff9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199ad5c)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff8199df50)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/acpi_pcc.c (ffffffff819c0cf5)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a280db)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81de2019)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e31dc)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff819e65c0)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81a0b716)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a732a9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81e97fe9)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_ioremap(acpi_physical_address phys, acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763d48)
Location: arch/arm64/include/asm/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a96f8)
Location: arch/arm64/include/asm/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffff800010b7be88)
Location: arch/arm64/include/asm/acpi.h:49
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffff800010b7be88-ffff800010b7bedc: acpi_os_ioremap (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca08b)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff815cbd02)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160a261)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff828ff065)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b310b)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff815b4d52)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fbea1)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff828f6b6a)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca60b)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff815cccb2)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81632671)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff829142f7)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e449d)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/nvs.c (ffffffff815e6b52)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:suspend_nvs_save
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164c9a1)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8291afbe)
Location: include/acpi/acpi_io.h:10
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
