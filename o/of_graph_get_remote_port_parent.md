# Function: <code>of_graph_get_remote_port_parent</code>

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
struct device_node *of_graph_get_remote_port_parent(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6f910)
Location: drivers/of/property.c:732
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
ffff800010b6f910-ffff800010b6f988: of_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_graph_get_remote_port_parent(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c52580)
Location: drivers/of/property.c:732
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c:omapdss_walk_device
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
c0c52580-c0c525d0: of_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_graph_get_remote_port_parent(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c4ad20)
Location: drivers/of/property.c:732
Inline: False
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
c000000000c4ad20-c000000000c4adcc: of_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_graph_get_remote_port_parent(const struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000723c94)
Location: drivers/of/property.c:732
Inline: False
Direct callers:
  - drivers/of/property.c:of_graph_get_remote_node
```
**Symbols:**

```
ffffffe000723c94-ffffffe000723cf4: of_graph_get_remote_port_parent (STB_GLOBAL)
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
