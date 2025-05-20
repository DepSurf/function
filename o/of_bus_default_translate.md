# Function: <code>of_bus_default_translate</code>

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
int of_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b72d80)
Location: drivers/of/address.c:84
Inline: False
Direct callers:
  - drivers/of/address.c:of_bus_pci_translate
```
**Symbols:**

```
ffff800010b72d80-ffff800010b72e78: of_bus_default_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c54e04)
Location: drivers/of/address.c:84
Inline: False
Direct callers:
  - drivers/of/address.c:of_bus_pci_translate
```
**Symbols:**

```
c0c54e04-c0c54ea4: of_bus_default_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4f090)
Location: drivers/of/address.c:84
Inline: False
Direct callers:
  - drivers/of/address.c:of_bus_isa_translate
  - drivers/of/address.c:of_bus_pci_translate
```
**Symbols:**

```
c000000000c4f090-c000000000c4f1b4: of_bus_default_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_bus_default_translate(__be32 *addr, u64 offset, int na);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe00072685c)
Location: drivers/of/address.c:84
Inline: False
Direct callers:
  - drivers/of/address.c:of_bus_pci_translate
```
**Symbols:**

```
ffffffe00072685c-ffffffe00072696a: of_bus_default_translate (STB_LOCAL)
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
