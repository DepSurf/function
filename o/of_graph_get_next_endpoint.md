# Function: <code>of_graph_get_next_endpoint</code>

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
struct device_node *of_graph_get_next_endpoint(const struct device_node *parent, struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6f028)
Location: drivers/of/property.c:595
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
```
**Symbols:**

```
ffff800010b6f028-ffff800010b6f158: of_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_graph_get_next_endpoint(const struct device_node *parent, struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c51db8)
Location: drivers/of/property.c:595
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c:omapdss_walk_device
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
```
**Symbols:**

```
c0c51db8-c0c51ef0: of_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_graph_get_next_endpoint(const struct device_node *parent, struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c4a0f0)
Location: drivers/of/property.c:595
Inline: False
Direct callers:
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
```
**Symbols:**

```
c000000000c4a0f0-c000000000c4a2b4: of_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_graph_get_next_endpoint(const struct device_node *parent, struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe0007235a8)
Location: drivers/of/property.c:595
Inline: False
Direct callers:
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_count
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
  - drivers/of/property.c:of_graph_get_endpoint_by_regs
```
**Symbols:**

```
ffffffe0007235a8-ffffffe0007236b2: of_graph_get_next_endpoint (STB_GLOBAL)
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
