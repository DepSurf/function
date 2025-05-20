# Function: <code>software_node_to_swnode</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e36d0)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816e36d0-ffffffff816e373b: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817086e0)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817086e0-ffffffff8170874b: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c30f0)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817c30f0-ffffffff817c315e: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7f30)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817d7f30-ffffffff817d7fa1: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bbdf0)
Location: drivers/base/swnode.c:66
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff817bbdf0-ffffffff817bbe59: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81845f90)
Location: drivers/base/swnode.c:68
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81845f90-ffffffff81845ff9: software_node_to_swnode (STB_LOCAL)
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
In drivers/base/swnode.c (ffffffff8198b4c5)
Location: drivers/base/swnode.c:68
Inline: True
Inline callers:
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
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
In drivers/base/swnode.c (ffffffff81afa9e5)
Location: drivers/base/swnode.c:68
Inline: True
Inline callers:
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
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
In drivers/base/swnode.c (ffffffff81b48dd5)
Location: drivers/base/swnode.c:68
Inline: True
Inline callers:
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
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
In drivers/base/swnode.c (ffffffff81ba11c5)
Location: drivers/base/swnode.c:68
Inline: True
Inline callers:
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
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
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f5ef0)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffff8000108f5ef0-ffff8000108f5fcc: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1578)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
c09e1578-c09e160c: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000990dc0)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
c000000000990dc0-c000000000990eb0: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586f4e)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffe000586f4e-ffffffe000587000: software_node_to_swnode (STB_LOCAL)
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
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cde30)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816cde30-ffffffff816cde9b: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a9160)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816a9160-ffffffff816a91cb: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc3a0)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff816fc3a0-ffffffff816fc40b: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct swnode *software_node_to_swnode(const struct software_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81715e30)
Location: drivers/base/swnode.c:52
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_register
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
```
**Symbols:**

```
ffffffff81715e30-ffffffff81715e9e: software_node_to_swnode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
