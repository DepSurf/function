# Function: <code>of_match_bus</code>

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
struct of_bus *of_match_bus(struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b72598)
Location: drivers/of/address.c:465
Inline: False
Direct callers:
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_get_pci_address
```
**Symbols:**

```
ffff800010b72598-ffff800010b72604: of_match_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct of_bus *of_match_bus(struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c54a80)
Location: drivers/of/address.c:465
Inline: False
Direct callers:
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_get_pci_address
```
**Symbols:**

```
c0c54a80-c0c54ae4: of_match_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct of_bus *of_match_bus(struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4ea50)
Location: drivers/of/address.c:465
Inline: False
Direct callers:
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_get_pci_address
```
**Symbols:**

```
c000000000c4ea50-c000000000c4eaf8: of_match_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct of_bus *of_match_bus(struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe00072624a)
Location: drivers/of/address.c:465
Inline: False
Direct callers:
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_get_pci_address
```
**Symbols:**

```
ffffffe00072624a-ffffffe0007262aa: of_match_bus (STB_LOCAL)
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
