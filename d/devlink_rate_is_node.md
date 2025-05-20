# Function: <code>devlink_rate_is_node</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af2f06)
Location: net/core/devlink.c:201
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_rate_nodes_destroy
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_rate_node_get_from_attrs
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
In net/core/devlink.c (ffffffff81c76d74)
Location: net/core/devlink.c:352
Inline: True
Inline callers:
  - net/core/devlink.c:devl_rate_nodes_destroy
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_rate_node_get_from_attrs
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
In net/core/devlink.c (ffffffff81e2fb44)
Location: net/core/devlink.c:421
Inline: True
Inline callers:
  - net/core/devlink.c:devl_rate_nodes_destroy
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_rate_node_get_from_attrs
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
In net/devlink/leftover.c (ffffffff8203321a)
Location: net/devlink/leftover.c:187
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_rate_nodes_destroy
  - net/devlink/leftover.c:devlink_rate_nodes_check
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
  - net/devlink/leftover.c:devlink_rate_node_get_from_attrs
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
In net/devlink/rate.c (ffffffff8211802a)
Location: net/devlink/rate.c:16
Inline: True
Inline callers:
  - net/devlink/rate.c:devl_rate_nodes_destroy
  - net/devlink/rate.c:devlink_rate_nodes_check
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
  - net/devlink/rate.c:devlink_rate_node_get_from_attrs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
