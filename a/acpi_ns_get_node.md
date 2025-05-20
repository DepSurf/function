# Function: <code>acpi_ns_get_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8149f396)
Location: drivers/acpi/acpica/nsutils.c:685
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffffffff8149f396-ffffffff8149f49a: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee6a8)
Location: drivers/acpi/acpica/nsutils.c:686
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffffffff814ee6a8-ffffffff814ee7b0: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815111e8)
Location: drivers/acpi/acpica/nsutils.c:764
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffffffff815111e8-ffffffff81511240: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815218b7)
Location: drivers/acpi/acpica/nsutils.c:759
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffffffff815218b7-ffffffff8152190f: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81575baa)
Location: drivers/acpi/acpica/nsutils.c:759
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff81575baa-ffffffff81575c5f: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815acb1c)
Location: drivers/acpi/acpica/nsutils.c:725
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff815acb1c-ffffffff815acbd1: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815c5b13)
Location: drivers/acpi/acpica/nsutils.c:725
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff815c5b13-ffffffff815c5bc8: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f73f6)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff815f73f6-ffffffff815f74ae: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8161889c)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff8161889c-ffffffff81618954: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4da3)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff816c4da3-ffffffff816c4e5b: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816e2de7)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff816e2de7-ffffffff816e2e9f: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4cc3)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff816c4cc3-ffffffff816c4d7b: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8173c028)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff8173c028-ffffffff8173c0e0: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8186d71c)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff8186d71c-ffffffff8186d7e0: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819ad440)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff819ad440-ffffffff819ad523: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819f4310)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff819f4310-ffffffff819f43f3: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3f130)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff81a3f130-ffffffff81a3f213: acpi_ns_get_node (STB_GLOBAL)
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
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffff800010790608)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffff800010790608-ffff80001079067c: acpi_ns_get_node (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f5e86)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffffffff815f5e86-ffffffff815f5ee3: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815e13e0)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
```
**Symbols:**

```
ffffffff815e13e0-ffffffff815e143d: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8160cb7c)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff8160cb7c-ffffffff8160cc34: acpi_ns_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81626a2c)
Location: drivers/acpi/acpica/nsutils.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_TSS
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
```
**Symbols:**

```
ffffffff81626a2c-ffffffff81626ae4: acpi_ns_get_node (STB_GLOBAL)
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
