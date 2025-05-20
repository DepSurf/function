# Function: <code>acpi_fwnode_get_named_child_node</code>

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
struct fwnode_handle *acpi_fwnode_get_named_child_node(struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150b400)
Location: drivers/acpi/property.c:1174
Inline: False
```
**Symbols:**

```
ffffffff8150b400-ffffffff8150b463: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e2f0)
Location: drivers/acpi/property.c:1190
Inline: False
```
**Symbols:**

```
ffffffff8154e2f0-ffffffff8154e361: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815847e0)
Location: drivers/acpi/property.c:1190
Inline: False
```
**Symbols:**

```
ffffffff815847e0-ffffffff81584851: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159c960)
Location: drivers/acpi/property.c:602
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8159c960-ffffffff8159c9d1: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce0a0)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815ce0a0-ffffffff815ce18b: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef320)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815ef320-ffffffff815ef40b: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b530)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8169b530-ffffffff8169b61b: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8390)
Location: drivers/acpi/property.c:609
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff816b8390-ffffffff816b8438: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a330)
Location: drivers/acpi/property.c:609
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8169a330-ffffffff8169a3d8: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710190)
Location: drivers/acpi/property.c:609
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff81710190-ffffffff81710238: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183ed60)
Location: drivers/acpi/property.c:616
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8183ed60-ffffffff8183ee1e: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81975340)
Location: drivers/acpi/property.c:775
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff81975340-ffffffff819753f7: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bbb80)
Location: drivers/acpi/property.c:775
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff819bbb80-ffffffff819bbc37: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a06880)
Location: drivers/acpi/property.c:779
Inline: False
```
**Symbols:**

```
ffffffff81a06880-ffffffff81a06937: acpi_fwnode_get_named_child_node (STB_LOCAL)
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
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff800010779fa0)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffff800010779fa0-ffff80001077a0c0: acpi_fwnode_get_named_child_node (STB_LOCAL)
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
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ddfb0)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815ddfb0-ffffffff815de09b: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c95f0)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815c95f0-ffffffff815c96db: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3600)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815e3600-ffffffff815e36eb: acpi_fwnode_get_named_child_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *acpi_fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd4c0)
Location: drivers/acpi/property.c:606
Inline: False
Direct callers:
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815fd4c0-ffffffff815fd5ab: acpi_fwnode_get_named_child_node (STB_LOCAL)
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
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
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
