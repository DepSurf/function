# Function: <code>acpi_ns_get_next_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8149f49a)
Location: drivers/acpi/acpica/nswalk.c:68
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
```
**Symbols:**

```
ffffffff8149f49a-ffffffff8149f4b4: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff814ee845)
Location: drivers/acpi/acpica/nswalk.c:68
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff814ee7b0-ffffffff814ee7ca: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815112d5)
Location: drivers/acpi/acpica/nswalk.c:68
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff81511240-ffffffff8151125a: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81521995)
Location: drivers/acpi/acpica/nswalk.c:68
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff8152190f-ffffffff81521929: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81575d2d)
Location: drivers/acpi/acpica/nswalk.c:68
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff81575c5f-ffffffff81575c8b: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815acc9f)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff815acbd1-ffffffff815acbfd: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815c5c96)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff815c5bc8-ffffffff815c5bf4: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815f757c)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff815f74ae-ffffffff815f74da: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81618a22)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff81618954-ffffffff81618980: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816c4f29)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff816c4e5b-ffffffff816c4e87: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816e2f6d)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff816e2e9f-ffffffff816e2ecb: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816c4e49)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff816c4d7b-ffffffff816c4da7: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8173c1ae)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff8173c0e0-ffffffff8173c10c: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8186d8f2)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff8186d7e0-ffffffff8186d814: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff819ad654)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff819ad540-ffffffff819ad57f: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff819f4524)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff819f4410-ffffffff819f444f: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81a3f344)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff81a3f230-ffffffff81a3f26f: acpi_ns_get_next_node (STB_GLOBAL)
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
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffff800010790764)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffff80001079067c-ffff8000107906b4: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815f5f65)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff815f5ee3-ffffffff815f5efd: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815e14bf)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff815e143d-ffffffff815e1457: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8160cd02)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff8160cc34-ffffffff8160cc60: acpi_ns_get_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct acpi_namespace_node *acpi_ns_get_next_node(struct acpi_namespace_node *parent_node, struct acpi_namespace_node *child_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81626bb2)
Location: drivers/acpi/acpica/nswalk.c:34
Inline: True
Inline callers:
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
```
**Symbols:**

```
ffffffff81626ae4-ffffffff81626b10: acpi_ns_get_next_node (STB_GLOBAL)
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
