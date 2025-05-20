# Function: <code>acpi_ns_get_node_unlocked</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81510b5e)
Location: drivers/acpi/acpica/nsutils.c:686
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff81510b5e-ffffffff81510b7d: acpi_ns_get_node_unlocked.part.1 (STB_LOCAL)
ffffffff81511110-ffffffff815111e8: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8152121c)
Location: drivers/acpi/acpica/nsutils.c:681
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff8152121c-ffffffff8152123b: acpi_ns_get_node_unlocked.part.1 (STB_LOCAL)
ffffffff815217df-ffffffff815218b7: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815759ce)
Location: drivers/acpi/acpica/nsutils.c:681
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff815759ce-ffffffff81575baa: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815ac940)
Location: drivers/acpi/acpica/nsutils.c:647
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff815ac940-ffffffff815acb1c: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815c5937)
Location: drivers/acpi/acpica/nsutils.c:647
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff815c5937-ffffffff815c5b13: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f721b)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff815f721b-ffffffff815f73f6: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816186c1)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff816186c1-ffffffff8161889c: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4bdd)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff816c4bdd-ffffffff816c4da3: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816e2c21)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff816e2c21-ffffffff816e2de7: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4ae8)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff816c4ae8-ffffffff816c4cc3: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8173be4d)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff8173be4d-ffffffff8173c028: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8186d515)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff8186d515-ffffffff8186d71c: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819ad200)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff819ad200-ffffffff819ad42a: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819f40d0)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff819f40d0-ffffffff819f42fa: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3eef0)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff81a3eef0-ffffffff81a3f11a: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffff80001078fdc0)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffff80001078fdc0-ffff80001078fe00: acpi_ns_get_node_unlocked.part.0 (STB_LOCAL)
ffff80001079051c-ffff800010790608: acpi_ns_get_node_unlocked (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f5828)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff815f5828-ffffffff815f5847: acpi_ns_get_node_unlocked.part.0 (STB_LOCAL)
ffffffff815f5daf-ffffffff815f5e86: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815e0db3)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff815e0db3-ffffffff815e0dd2: acpi_ns_get_node_unlocked.part.0 (STB_LOCAL)
ffffffff815e1309-ffffffff815e13e0: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8160c9a1)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff8160c9a1-ffffffff8160cb7c: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node *prefix_node, const char *pathname, u32 flags, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81626851)
Location: drivers/acpi/acpica/nsutils.c:635
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff81626851-ffffffff81626a2c: acpi_ns_get_node_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
