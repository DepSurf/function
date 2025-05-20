# Function: <code>acpi_nondev_subnode_data_ok</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fbd79)
Location: drivers/acpi/property.c:92
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff814fbd79-ffffffff814fbe11: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150c090)
Location: drivers/acpi/property.c:98
Inline: False
```
**Symbols:**

```
ffffffff8150c090-ffffffff8150c138: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154ede0)
Location: drivers/acpi/property.c:95
Inline: False
```
**Symbols:**

```
ffffffff8154ede0-ffffffff8154ee88: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81585680)
Location: drivers/acpi/property.c:95
Inline: False
```
**Symbols:**

```
ffffffff81585680-ffffffff81585728: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159da10)
Location: drivers/acpi/property.c:111
Inline: False
```
**Symbols:**

```
ffffffff8159da10-ffffffff8159dab6: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cef40)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffffffff815cef40-ffffffff815cefe9: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815f01c0)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffffffff815f01c0-ffffffff815f0269: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c3c0)
Location: drivers/acpi/property.c:115
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
```
**Symbols:**

```
ffffffff8169c3c0-ffffffff8169c468: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b9250)
Location: drivers/acpi/property.c:118
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
```
**Symbols:**

```
ffffffff816b9250-ffffffff816b92f8: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b250)
Location: drivers/acpi/property.c:118
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff8169b250-ffffffff8169b2f8: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff817110f0)
Location: drivers/acpi/property.c:118
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff817110f0-ffffffff81711198: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183fe80)
Location: drivers/acpi/property.c:118
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff8183fe80-ffffffff8183ff2c: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81976460)
Location: drivers/acpi/property.c:123
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff81976460-ffffffff8197650c: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bcdd0)
Location: drivers/acpi/property.c:123
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff819bcdd0-ffffffff819bce7c: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a07c80)
Location: drivers/acpi/property.c:127
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff81a07c80-ffffffff81a07d2c: acpi_nondev_subnode_data_ok (STB_LOCAL)
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
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077b170)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffff80001077b170-ffff80001077b22c: acpi_nondev_subnode_data_ok (STB_LOCAL)
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
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815dee50)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffffffff815dee50-ffffffff815deef9: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ca490)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffffffff815ca490-ffffffff815ca539: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e44a0)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffffffff815e44a0-ffffffff815e4549: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_nondev_subnode_data_ok(acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fe360)
Location: drivers/acpi/property.c:115
Inline: False
```
**Symbols:**

```
ffffffff815fe360-ffffffff815fe409: acpi_nondev_subnode_data_ok (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_handle *parent</code>
</li>
</ul>
</details>
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
