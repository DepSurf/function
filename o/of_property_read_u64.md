# Function: <code>of_property_read_u64</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_property_read_u64(const struct device_node *np, const char *propname, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6fa98)
Location: drivers/of/property.c:315
Inline: False
Direct callers:
  - arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_init
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
```
**Symbols:**

```
ffff800010b6fa98-ffff800010b6fb44: of_property_read_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_property_read_u64(const struct device_node *np, const char *propname, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c513b0)
Location: drivers/of/property.c:315
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_prepare_cpus
  - drivers/mmc/host/sdhci.c:__sdhci_read_caps
  - drivers/mmc/host/sdhci.c:__sdhci_read_caps
```
**Symbols:**

```
c0c513b0-c0c51430: of_property_read_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_property_read_u64(const struct device_node *np, const char *propname, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c49040)
Location: drivers/of/property.c:315
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal-msglog.c:memcons_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_get_slot_id
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
```
**Symbols:**

```
c000000000c49040-c000000000c49118: of_property_read_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_property_read_u64(const struct device_node *np, const char *propname, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000723df2)
Location: drivers/of/property.c:315
Inline: False
```
**Symbols:**

```
ffffffe000723df2-ffffffe000723ec2: of_property_read_u64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
