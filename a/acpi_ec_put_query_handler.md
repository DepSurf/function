# Function: <code>acpi_ec_put_query_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81483313)
Location: drivers/acpi/ec.c:973
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d1db6)
Location: drivers/acpi/ec.c:980
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f4158)
Location: drivers/acpi/ec.c:1060
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ec_put_query_handler(struct acpi_ec_query_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81501a60)
Location: drivers/acpi/ec.c:1071
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
**Symbols:**

```
ffffffff81501a60-ffffffff81501a78: acpi_ec_put_query_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8154435b)
Location: drivers/acpi/ec.c:1073
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157a41b)
Location: drivers/acpi/ec.c:1079
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8159216b)
Location: drivers/acpi/ec.c:1091
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c306c)
Location: drivers/acpi/ec.c:1105
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e439c)
Location: drivers/acpi/ec.c:1079
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
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
In drivers/acpi/ec.c (ffffffff8168f6bc)
Location: drivers/acpi/ec.c:1067
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
In drivers/acpi/ec.c (ffffffff816ad38c)
Location: drivers/acpi/ec.c:1054
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
In drivers/acpi/ec.c (ffffffff8168f9ac)
Location: drivers/acpi/ec.c:1055
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
In drivers/acpi/ec.c (ffffffff8170547c)
Location: drivers/acpi/ec.c:1057
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
In drivers/acpi/ec.c (ffffffff8183379a)
Location: drivers/acpi/ec.c:1080
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
In drivers/acpi/ec.c (ffffffff8196735a)
Location: drivers/acpi/ec.c:1077
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
In drivers/acpi/ec.c (ffffffff819ad92a)
Location: drivers/acpi/ec.c:1062
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
In drivers/acpi/ec.c (ffffffff819f7daa)
Location: drivers/acpi/ec.c:1062
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
In drivers/acpi/ec.c (ffff800010770084)
Location: drivers/acpi/ec.c:1079
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d628c)
Location: drivers/acpi/ec.c:1079
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815bfe4c)
Location: drivers/acpi/ec.c:1079
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d867c)
Location: drivers/acpi/ec.c:1079
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f253c)
Location: drivers/acpi/ec.c:1079
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
