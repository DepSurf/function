# Function: <code>of_property_read_u64_index</code>

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
int of_property_read_u64_index(const struct device_node *np, const char *propname, u32 index, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6e650)
Location: drivers/of/property.c:145
Inline: False
```
**Symbols:**

```
ffff800010b6e650-ffff800010b6e6fc: of_property_read_u64_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_property_read_u64_index(const struct device_node *np, const char *propname, u32 index, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c514f8)
Location: drivers/of/property.c:145
Inline: False
```
**Symbols:**

```
c0c514f8-c0c5158c: of_property_read_u64_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_property_read_u64_index(const struct device_node *np, const char *propname, u32 index, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c49210)
Location: drivers/of/property.c:145
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_map_xsl_regs
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
```
**Symbols:**

```
c000000000c49210-c000000000c492ec: of_property_read_u64_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_property_read_u64_index(const struct device_node *np, const char *propname, u32 index, u64 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000722df8)
Location: drivers/of/property.c:145
Inline: False
```
**Symbols:**

```
ffffffe000722df8-ffffffe000722ee4: of_property_read_u64_index (STB_GLOBAL)
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
