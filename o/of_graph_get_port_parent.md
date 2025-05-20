# Function: <code>of_graph_get_port_parent</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *of_graph_get_port_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/property.c (ffff800010b6f940)
Location: drivers/of/property.c:702
Inline: True
Inline callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
ffff800010b6f848-ffff800010b6f8c4: of_graph_get_port_parent.part.0 (STB_LOCAL)
ffff800010b6f8c8-ffff800010b6f910: of_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *of_graph_get_port_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/property.c (c0c525a4)
Location: drivers/of/property.c:702
Inline: True
Inline callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
  - sound/soc/soc-core.c:snd_soc_get_dai_id
```
**Symbols:**

```
c0c524d4-c0c5254c: of_graph_get_port_parent.part.0 (STB_LOCAL)
c0c5254c-c0c52580: of_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *of_graph_get_port_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/property.c (c000000000c4ad58)
Location: drivers/of/property.c:702
Inline: True
Inline callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
c000000000c4ac00-c000000000c4acb8: of_graph_get_port_parent.part.0 (STB_LOCAL)
c000000000c4acc0-c000000000c4ad1c: of_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *of_graph_get_port_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/property.c (ffffffe000723cc2)
Location: drivers/of/property.c:702
Inline: True
Inline callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffe000723bf2-ffffffe000723c52: of_graph_get_port_parent.part.0 (STB_LOCAL)
ffffffe000723c52-ffffffe000723c94: of_graph_get_port_parent (STB_GLOBAL)
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
