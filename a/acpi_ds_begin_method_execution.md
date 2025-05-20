# Function: <code>acpi_ds_begin_method_execution</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8148c5b3)
Location: drivers/acpi/acpica/dsmethod.c:323
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8148c5b3-ffffffff8148c78b: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff814db3b1)
Location: drivers/acpi/acpica/dsmethod.c:322
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff814db3b1-ffffffff814db5a0: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff814fdca8)
Location: drivers/acpi/acpica/dsmethod.c:322
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff814fdca8-ffffffff814fde97: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8150e16f)
Location: drivers/acpi/acpica/dsmethod.c:326
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8150e16f-ffffffff8150e35e: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815526e3)
Location: drivers/acpi/acpica/dsmethod.c:326
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815526e3-ffffffff81552a6a: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8158902b)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8158902b-ffffffff815893b4: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815a156d)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815a156d-ffffffff815a18f6: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815d2bca)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815d2bca-ffffffff815d2f53: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815f3e3d)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815f3e3d-ffffffff815f41c7: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8169ff9b)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8169ff9b-ffffffff816a0250: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff816bd7b3)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816bd7b3-ffffffff816bda68: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8169f7be)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8169f7be-ffffffff8169fb48: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff81715dbe)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81715dbe-ffffffff81716148: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff818458c4)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff818458c4-ffffffff81845c6b: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8197d260)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8197d260-ffffffff8197d67e: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff819c3d10)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff819c3d10-ffffffff819c412e: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0e730)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81a0e730-ffffffff81a0eb4e: acpi_ds_begin_method_execution (STB_GLOBAL)
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
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffff80001077dad8)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffff80001077dad8-ffff80001077dcfc: acpi_ds_begin_method_execution (STB_GLOBAL)
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
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e1830)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815e1830-ffffffff815e1a20: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815cceab)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815cceab-ffffffff815cd09b: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e811d)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815e811d-ffffffff815e84a7: acpi_ds_begin_method_execution (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ds_begin_method_execution(struct acpi_namespace_node *method_node, union acpi_operand_object *obj_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff81601fcd)
Location: drivers/acpi/acpica/dsmethod.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81601fcd-ffffffff81602357: acpi_ds_begin_method_execution (STB_GLOBAL)
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
