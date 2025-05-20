# Function: <code>software_node_get</code>

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
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa050)
Location: drivers/base/swnode.c:431
Inline: False
```
**Symbols:**

```
ffffffff816aa050-ffffffff816aa09b: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e38f0)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816e38f0-ffffffff816e393b: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707b30)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81707b30-ffffffff81707b7b: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c37e8)
Location: drivers/base/swnode.c:350
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817c27f0-ffffffff817c2830: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d8788)
Location: drivers/base/swnode.c:350
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817d7540-ffffffff817d7580: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc3b5)
Location: drivers/base/swnode.c:364
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817bb0b0-ffffffff817bb0ef: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846615)
Location: drivers/base/swnode.c:366
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81845320-ffffffff8184535f: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a3aa)
Location: drivers/base/swnode.c:366
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81989550-ffffffff81989595: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af979a)
Location: drivers/base/swnode.c:366
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81af8800-ffffffff81af8845: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b47d50)
Location: drivers/base/swnode.c:366
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81b46d30-ffffffff81b46d75: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba00e0)
Location: drivers/base/swnode.c:366
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81b9f090-ffffffff81b9f0d5: software_node_get (STB_LOCAL)
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
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f54b0)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffff8000108f54b0-ffff8000108f550c: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1900)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
c09e1900-c09e1950: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c00000000098fb90)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
c00000000098fb90-c00000000098fc18: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe0005866ae)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffe0005866ae-ffffffe0005866fa: software_node_get (STB_LOCAL)
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
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd280)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816cd280-ffffffff816cd2cb: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a85b0)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816a85b0-ffffffff816a85fb: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb7f0)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816fb7f0-ffffffff816fb83b: software_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *software_node_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716120)
Location: drivers/base/swnode.c:473
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81716120-ffffffff8171616b: software_node_get (STB_LOCAL)
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
