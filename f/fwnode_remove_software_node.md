# Function: <code>fwnode_remove_software_node</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa010)
Location: drivers/base/swnode.c:608
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff816aa010-ffffffff816aa046: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e39c0)
Location: drivers/base/swnode.c:800
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff816e39c0-ffffffff816e3a43: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707c00)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff81707c00-ffffffff81707c83: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c38de)
Location: drivers/base/swnode.c:839
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_nodes
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff817c2a10-ffffffff817c2a46: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d8061)
Location: drivers/base/swnode.c:842
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_unregister_nodes
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff817d7820-ffffffff817d7856: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bbf7b)
Location: drivers/base/swnode.c:1007
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_unregister_nodes
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff817bb400-ffffffff817bb432: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8184611b)
Location: drivers/base/swnode.c:1009
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_unregister_nodes
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff81845670-ffffffff818456a2: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a78e)
Location: drivers/base/swnode.c:1003
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff81989900-ffffffff8198993b: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af9bde)
Location: drivers/base/swnode.c:1003
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff81af8c20-ffffffff81af8c5b: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b47150)
Location: drivers/base/swnode.c:942
Inline: True
```
**Symbols:**

```
ffffffff81b47150-ffffffff81b4718b: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b9f4b0)
Location: drivers/base/swnode.c:945
Inline: True
```
**Symbols:**

```
ffffffff81b9f4b0-ffffffff81b9f4eb: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f55c8)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffff8000108f55c8-ffff8000108f566c: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e19ec)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
c09e19ec-c09e1a78: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000990010)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
c000000000990010-c000000000990114: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586868)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffe000586868-ffffffe0005868f4: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd350)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff816cd350-ffffffff816cd3d3: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8680)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff816a8680-ffffffff816a8703: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb8c0)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff816fb8c0-ffffffff816fb943: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817161f0)
Location: drivers/base/swnode.c:840
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/swnode.c:software_node_unregister_nodes
```
**Symbols:**

```
ffffffff817161f0-ffffffff81716273: fwnode_remove_software_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
