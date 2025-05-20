# Function: <code>of_graph_get_endpoint_by_regs</code>

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
struct device_node *of_graph_get_endpoint_by_regs(const struct device_node *parent, int port_reg, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6f158)
Location: drivers/of/property.c:664
Inline: False
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
ffff800010b6f158-ffff800010b6f228: of_graph_get_endpoint_by_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_graph_get_endpoint_by_regs(const struct device_node *parent, int port_reg, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c51ef0)
Location: drivers/of/property.c:664
Inline: False
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
c0c51ef0-c0c51fb4: of_graph_get_endpoint_by_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_graph_get_endpoint_by_regs(const struct device_node *parent, int port_reg, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c4a2c0)
Location: drivers/of/property.c:664
Inline: False
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
c000000000c4a2c0-c000000000c4a3d0: of_graph_get_endpoint_by_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_graph_get_endpoint_by_regs(const struct device_node *parent, int port_reg, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe0007236b2)
Location: drivers/of/property.c:664
Inline: False
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
ffffffe0007236b2-ffffffe000723746: of_graph_get_endpoint_by_regs (STB_GLOBAL)
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
