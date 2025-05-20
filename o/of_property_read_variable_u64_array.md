# Function: <code>of_property_read_variable_u64_array</code>

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
int of_property_read_variable_u64_array(const struct device_node *np, const char *propname, u64 *out_values, size_t sz_min, size_t sz_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6fb48)
Location: drivers/of/property.c:350
Inline: False
Direct callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
```
**Symbols:**

```
ffff800010b6fb48-ffff800010b6fc24: of_property_read_variable_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_property_read_variable_u64_array(const struct device_node *np, const char *propname, u64 *out_values, size_t sz_min, size_t sz_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c51430)
Location: drivers/of/property.c:350
Inline: False
Direct callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
```
**Symbols:**

```
c0c51430-c0c514f8: of_property_read_variable_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_property_read_variable_u64_array(const struct device_node *np, const char *propname, u64 *out_values, size_t sz_min, size_t sz_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c49120)
Location: drivers/of/property.c:350
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
  - drivers/of/property.c:of_fwnode_property_read_int_array
```
**Symbols:**

```
c000000000c49120-c000000000c49210: of_property_read_variable_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_property_read_variable_u64_array(const struct device_node *np, const char *propname, u64 *out_values, size_t sz_min, size_t sz_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000723ec2)
Location: drivers/of/property.c:350
Inline: False
Direct callers:
  - drivers/of/property.c:of_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffe000723ec2-ffffffe000723fa6: of_property_read_variable_u64_array (STB_GLOBAL)
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
