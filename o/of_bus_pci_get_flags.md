# Function: <code>of_bus_pci_get_flags</code>

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
unsigned int of_bus_pci_get_flags(const __be32 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b72500)
Location: drivers/of/address.c:126
Inline: False
Direct callers:
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
```
**Symbols:**

```
ffff800010b72500-ffff800010b72558: of_bus_pci_get_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c55f3c)
Location: drivers/of/address.c:126
Inline: True
Inline callers:
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
```
**Symbols:**

```
c0c54a10-c0c54a58: of_bus_pci_get_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c509e0)
Location: drivers/of/address.c:126
Inline: True
Inline callers:
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
```
**Symbols:**

```
c000000000c4e9c0-c000000000c4ea18: of_bus_pci_get_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int of_bus_pci_get_flags(const __be32 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe0007261a6)
Location: drivers/of/address.c:126
Inline: False
Direct callers:
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
```
**Symbols:**

```
ffffffe0007261a6-ffffffe00072621a: of_bus_pci_get_flags (STB_LOCAL)
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
