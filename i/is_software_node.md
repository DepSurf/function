# Function: <code>is_software_node</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aab3e)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff816aaaf0-ffffffff816aab18: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e472d)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff816e3760-ffffffff816e3788: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817089fd)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff81707990-ffffffff817079b8: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c3a8d)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff817c2600-ffffffff817c2628: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d880d)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff817d73f0-ffffffff817d7418: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc7d3)
Location: drivers/base/swnode.c:37
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff817baeb0-ffffffff817baed8: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846c5e)
Location: drivers/base/swnode.c:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff81845120-ffffffff81845148: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198b5ce)
Location: drivers/base/swnode.c:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
**Symbols:**

```
ffffffff81989350-ffffffff81989384: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afaafe)
Location: drivers/base/swnode.c:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff81af85c0-ffffffff81af85f4: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48eee)
Location: drivers/base/swnode.c:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff81b46af0-ffffffff81b46b24: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba12de)
Location: drivers/base/swnode.c:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff81b9ee50-ffffffff81b9ee84: is_software_node (STB_GLOBAL)
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
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f6740)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffff8000108f5268-ffff8000108f52bc: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e2788)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
c09e1700-c09e1740: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000991adc)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
c00000000098f760-c00000000098f7a8: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000587634)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffe0005864ee-ffffffe000586532: is_software_node (STB_GLOBAL)
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
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816ce14d)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff816cd0e0-ffffffff816cd108: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a947d)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff816a8410-ffffffff816a8438: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc6bd)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff816fb650-ffffffff816fb678: is_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716f5d)
Location: drivers/base/swnode.c:36
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
Direct callers:
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff81715f80-ffffffff81715fa8: is_software_node (STB_GLOBAL)
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
