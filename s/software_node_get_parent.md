# Function: <code>software_node_get_parent</code>

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
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a9f00)
Location: drivers/base/swnode.c:476
Inline: False
```
**Symbols:**

```
ffffffff816a9f00-ffffffff816a9f3f: software_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e38b0)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffff816e38b0-ffffffff816e38ef: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707ae0)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffff81707ae0-ffffffff81707b23: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c28f0)
Location: drivers/base/swnode.c:428
Inline: False
```
**Symbols:**

```
ffffffff817c28f0-ffffffff817c2933: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7700)
Location: drivers/base/swnode.c:428
Inline: False
```
**Symbols:**

```
ffffffff817d7700-ffffffff817d7743: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bb2e0)
Location: drivers/base/swnode.c:442
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff817bb2e0-ffffffff817bb326: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81845550)
Location: drivers/base/swnode.c:444
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81845550-ffffffff81845596: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198b133)
Location: drivers/base/swnode.c:441
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff819897c0-ffffffff8198981e: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afa623)
Location: drivers/base/swnode.c:441
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81af8ab0-ffffffff81af8b0e: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48a13)
Location: drivers/base/swnode.c:441
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81b46fe0-ffffffff81b4703e: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0e03)
Location: drivers/base/swnode.c:441
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81b9f340-ffffffff81b9f39e: software_node_get_parent (STB_LOCAL)
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
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f5440)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffff8000108f5440-ffff8000108f54ac: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e18a0)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
c09e18a0-c09e1900: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c00000000098fb10)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
c00000000098fb10-c00000000098fb8c: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586656)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffe000586656-ffffffe0005866ae: software_node_get_parent (STB_LOCAL)
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
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd230)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffff816cd230-ffffffff816cd273: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8560)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffff816a8560-ffffffff816a85a3: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb7a0)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffff816fb7a0-ffffffff816fb7e3: software_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817160d0)
Location: drivers/base/swnode.c:519
Inline: False
```
**Symbols:**

```
ffffffff817160d0-ffffffff81716113: software_node_get_parent (STB_LOCAL)
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
