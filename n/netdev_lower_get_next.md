# Function: <code>netdev_lower_get_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713a40)
Location: net/core/dev.c:5106
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff81713a40-ffffffff81713a68: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81786a65)
Location: net/core/dev.c:5450
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:netdev_default_l2upper_neigh_destroy
  - net/core/dev.c:netdev_default_l2upper_neigh_destroy
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_fwd_mark_reset
  - net/switchdev/switchdev.c:switchdev_port_fwd_mark_reset
  - net/switchdev/switchdev.c:switchdev_port_fwd_mark_get
  - net/switchdev/switchdev.c:switchdev_port_fwd_mark_get
  - net/switchdev/switchdev.c:switchdev_get_lowest_dev
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_port_attr_get
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff8177b6c0-ffffffff8177b6e8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b4025)
Location: net/core/dev.c:5658
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:netdev_default_l2upper_neigh_destroy
  - net/core/dev.c:netdev_default_l2upper_neigh_destroy
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:netdev_default_l2upper_neigh_construct
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_port_attr_get
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff817a8db0-ffffffff817a8dd8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d2c00)
Location: net/core/dev.c:5864
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_port_attr_get
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff817c7450-ffffffff817c7478: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184cf65)
Location: net/core/dev.c:6005
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_port_attr_get
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff81841030-ffffffff81841058: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818972e5)
Location: net/core/dev.c:6135
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_port_attr_get
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff8188b680-ffffffff8188b6a8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b9749)
Location: net/core/dev.c:6710
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_port_attr_get
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff818ac800-ffffffff818ac828: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819058ec)
Location: net/core/dev.c:6720
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff818f8040-ffffffff818f8068: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81937fdc)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81929f60-ffffffff81929f88: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ca43)
Location: net/core/dev.c:7164
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff819fdfa0-ffffffff819fdfc8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e1f3)
Location: net/core/dev.c:7326
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff819fdb30-ffffffff819fdb58: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4f91)
Location: net/core/dev.c:7585
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff819e4320-ffffffff819e4348: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa68e6)
Location: net/core/dev.c:7575
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
```
**Symbols:**

```
ffffffff81a94c20-ffffffff81a94c48: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1e69b)
Location: net/core/dev.c:7096
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81c0b160-ffffffff81c0b19c: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcfaf3)
Location: net/core/dev.c:7082
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81dbb140-ffffffff81dbb17c: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e40704)
Location: net/core/dev.c:7087
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81e2b8d0-ffffffff81e2b90c: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eff0b8)
Location: net/core/dev.c:7205
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81ee9930-ffffffff81ee996c: netdev_lower_get_next (STB_GLOBAL)
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
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd69a8)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffff800010bc6780-ffff800010bc67cc: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf1768)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
c0ce1cc4-c0ce1cf8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb6564)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
c000000000ca13b0-c000000000ca13e8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007600b0)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffe000752e36-ffffffe000752e76: netdev_lower_get_next (STB_GLOBAL)
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
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d7fac)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff818c9f60-ffffffff818c9f88: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891dec)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81883ea0-ffffffff81883ec8: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81928fdc)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff8191af60-ffffffff8191af88: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *netdev_lower_get_next(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194a6ac)
Location: net/core/dev.c:6773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff8193c160-ffffffff8193c188: netdev_lower_get_next (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
