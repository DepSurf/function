# Function: <code>property_entry_get</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa260)
Location: drivers/base/swnode.c:55
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816aa170-ffffffff816aa1af: property_entry_get.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3efa)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816e3b70-ffffffff816e3bb0: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8170885a)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff81707d60-ffffffff81707da0: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c371c)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_find
  - drivers/base/swnode.c:property_entry_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d86bc)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_find
  - drivers/base/swnode.c:property_entry_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc5fd)
Location: drivers/base/swnode.c:108
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8184669d)
Location: drivers/base/swnode.c:110
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a979)
Location: drivers/base/swnode.c:110
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af9df9)
Location: drivers/base/swnode.c:110
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48295)
Location: drivers/base/swnode.c:110
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0685)
Location: drivers/base/swnode.c:110
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f60f4)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffff8000108f5798-ffff8000108f57e8: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (c09e1fd0)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
c09e1bc0-c09e1c24: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (c000000000991168)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
c0000000009902d0-c0000000009904e0: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffe000587100)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffe0005869dc-ffffffe000586a20: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cdfaa)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816cd4b0-ffffffff816cd4f0: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a92da)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816a87e0-ffffffff816a8820: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc51a)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816fba20-ffffffff816fba60: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8171672a)
Location: drivers/base/swnode.c:94
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff817163a0-ffffffff817163e0: property_entry_get.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
