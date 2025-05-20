# Function: <code>acpi_ec_query_handler_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81482f0b)
Location: drivers/acpi/ec.c:965
Inline: False
```
**Symbols:**

```
ffffffff81482f0b-ffffffff81482f1f: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d1a1b)
Location: drivers/acpi/ec.c:972
Inline: False
```
**Symbols:**

```
ffffffff814d1a1b-ffffffff814d1a2f: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f3c77)
Location: drivers/acpi/ec.c:1052
Inline: False
```
**Symbols:**

```
ffffffff814f3c77-ffffffff814f3c8b: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81501a71)
Location: drivers/acpi/ec.c:1063
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_put_query_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81543ec0)
Location: drivers/acpi/ec.c:1065
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff81543ec0-ffffffff81543ed4: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81579e80)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff81579e80-ffffffff81579e94: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81591bb0)
Location: drivers/acpi/ec.c:1083
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff81591bb0-ffffffff81591bc4: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c2a80)
Location: drivers/acpi/ec.c:1097
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff815c2a80-ffffffff815c2a94: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e3e30)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff815e3e30-ffffffff815e3e44: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168f6f1)
Location: drivers/acpi/ec.c:1059
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ad3c1)
Location: drivers/acpi/ec.c:1046
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168f9e1)
Location: drivers/acpi/ec.c:1047
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff817054b1)
Location: drivers/acpi/ec.c:1049
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
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
In drivers/acpi/ec.c (ffffffff81833832)
Location: drivers/acpi/ec.c:1072
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
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
In drivers/acpi/ec.c (ffffffff819673f5)
Location: drivers/acpi/ec.c:1069
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
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
In drivers/acpi/ec.c (ffffffff819ad9c5)
Location: drivers/acpi/ec.c:1054
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
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
In drivers/acpi/ec.c (ffffffff819f7e45)
Location: drivers/acpi/ec.c:1054
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff8000107700a8)
Location: drivers/acpi/ec.c:1071
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
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
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d5d20)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff815d5d20-ffffffff815d5d34: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815bf8e0)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff815bf8e0-ffffffff815bf8f4: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d8110)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff815d8110-ffffffff815d8124: acpi_ec_query_handler_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_query_handler_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f1fd0)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff815f1fd0-ffffffff815f1fe4: acpi_ec_query_handler_release (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
