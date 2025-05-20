# Function: <code>of_graph_get_remote_endpoint</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_graph_get_remote_endpoint(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6f38c)
Location: drivers/of/property.c:688
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
ffff800010b6f318-ffff800010b6f350: of_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_graph_get_remote_endpoint(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c520ec)
Location: drivers/of/property.c:688
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
c0c52084-c0c520ac: of_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_graph_get_remote_endpoint(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c4a5b0)
Location: drivers/of/property.c:688
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
c000000000c4a520-c000000000c4a560: of_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_graph_get_remote_endpoint(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000723860)
Location: drivers/of/property.c:688
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/property.c:of_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffe0007237fc-ffffffe000723830: of_graph_get_remote_endpoint (STB_GLOBAL)
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
