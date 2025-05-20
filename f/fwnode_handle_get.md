# Function: <code>fwnode_handle_get</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e5f50)
Location: drivers/base/property.c:1004
Inline: False
```
**Symbols:**

```
ffffffff815e5f50-ffffffff815e5f75: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d290)
Location: drivers/base/property.c:1050
Inline: False
```
**Symbols:**

```
ffffffff8164d290-ffffffff8164d2bd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688bb0)
Location: drivers/base/property.c:1136
Inline: False
```
**Symbols:**

```
ffffffff81688bb0-ffffffff81688bdd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a88b0)
Location: drivers/base/property.c:659
Inline: False
```
**Symbols:**

```
ffffffff816a88b0-ffffffff816a88dd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e24a7)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
```
**Symbols:**

```
ffffffff816e19a0-ffffffff816e19cd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706657)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff81705b50-ffffffff81705b7d: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c1432)
Location: drivers/base/property.c:762
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_get_nth_parent
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff817c02c0-ffffffff817c02ed: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d62d2)
Location: drivers/base/property.c:814
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff817d5180-ffffffff817d51ad: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9d0a)
Location: drivers/base/property.c:814
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff817b8b90-ffffffff817b8bbd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818439e1)
Location: drivers/base/property.c:809
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81842820-ffffffff8184284d: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987737)
Location: drivers/base/property.c:809
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81986890-ffffffff819868d8: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af6057)
Location: drivers/base/property.c:817
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81af4f90-ffffffff81af4fd8: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b442b1)
Location: drivers/base/property.c:853
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81b431a0-ffffffff81b431e8: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c301)
Location: drivers/base/property.c:917
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81b9b070-ffffffff81b9b0b8: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3610)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffff8000108f2620-ffff8000108f2680: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dff2c)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
c09df264-c09df2a8: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d308)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
c00000000098c0a0-c00000000098c118: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584d6a)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffe0005841b4-ffffffe0005841fa: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbda7)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff816cb2a0-ffffffff816cb2cd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a70d7)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff816a65d0-ffffffff816a65fd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa317)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff816f9810-ffffffff816f983d: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_handle_get(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714bb7)
Location: drivers/base/property.c:683
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
Direct callers:
  - drivers/base/swnode.c:software_node_get_parent
```
**Symbols:**

```
ffffffff817140b0-ffffffff817140dd: fwnode_handle_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct fwnode_handle *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
