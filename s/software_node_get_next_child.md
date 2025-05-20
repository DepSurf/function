# Function: <code>software_node_get_next_child</code>

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
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a9f40)
Location: drivers/base/swnode.c:485
Inline: False
```
**Symbols:**

```
ffffffff816a9f40-ffffffff816a9fc7: software_node_get_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3820)
Location: drivers/base/swnode.c:527
Inline: False
```
**Symbols:**

```
ffffffff816e3820-ffffffff816e38a9: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707a50)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffffffff81707a50-ffffffff81707ad9: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2630)
Location: drivers/base/swnode.c:439
Inline: False
```
**Symbols:**

```
ffffffff817c2630-ffffffff817c26b9: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7640)
Location: drivers/base/swnode.c:439
Inline: False
```
**Symbols:**

```
ffffffff817d7640-ffffffff817d76f2: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bb1b0)
Location: drivers/base/swnode.c:453
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
```
**Symbols:**

```
ffffffff817bb1b0-ffffffff817bb25e: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81845420)
Location: drivers/base/swnode.c:455
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
```
**Symbols:**

```
ffffffff81845420-ffffffff818454ce: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81989660)
Location: drivers/base/swnode.c:452
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
```
**Symbols:**

```
ffffffff81989660-ffffffff81989732: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af8930)
Location: drivers/base/swnode.c:452
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
```
**Symbols:**

```
ffffffff81af8930-ffffffff81af8a02: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b46e60)
Location: drivers/base/swnode.c:452
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
```
**Symbols:**

```
ffffffff81b46e60-ffffffff81b46f32: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b9f1c0)
Location: drivers/base/swnode.c:452
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
```
**Symbols:**

```
ffffffff81b9f1c0-ffffffff81b9f292: software_node_get_next_child (STB_LOCAL)
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
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f5380)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffff8000108f5380-ffff8000108f5440: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e17e4)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
c09e17e4-c09e18a0: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c00000000098fa40)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
c00000000098fa40-c00000000098fb0c: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe0005865c6)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffffffe0005865c6-ffffffe000586656: software_node_get_next_child (STB_LOCAL)
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
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd1a0)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffffffff816cd1a0-ffffffff816cd229: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a84d0)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffffffff816a84d0-ffffffff816a8559: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb710)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffffffff816fb710-ffffffff816fb799: software_node_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_next_child(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716040)
Location: drivers/base/swnode.c:530
Inline: False
```
**Symbols:**

```
ffffffff81716040-ffffffff817160c9: software_node_get_next_child (STB_LOCAL)
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
