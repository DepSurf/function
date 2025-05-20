# Function: <code>acpi_add_nondev_subnodes</code>

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
In drivers/acpi/property.c (ffffffff8148a754)
Location: drivers/acpi/property.c:98
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff814d955c)
Location: drivers/acpi/property.c:98
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff814fbeb3)
Location: drivers/acpi/property.c:129
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff8150c20a)
Location: drivers/acpi/property.c:138
Inline: True
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
In drivers/acpi/property.c (ffffffff8154eb5a)
Location: drivers/acpi/property.c:135
Inline: True
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
In drivers/acpi/property.c (ffffffff81585430)
Location: drivers/acpi/property.c:135
Inline: True
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
In drivers/acpi/property.c (ffffffff8159db90)
Location: drivers/acpi/property.c:151
Inline: True
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
In drivers/acpi/property.c (ffffffff815cf0ac)
Location: drivers/acpi/property.c:155
Inline: True
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
In drivers/acpi/property.c (ffffffff815f032c)
Location: drivers/acpi/property.c:155
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_add_nondev_subnodes(acpi_handle scope, const union acpi_object *links, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c470)
Location: drivers/acpi/property.c:155
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff8169c470-ffffffff8169c58f: acpi_add_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_add_nondev_subnodes(acpi_handle scope, const union acpi_object *links, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b9300)
Location: drivers/acpi/property.c:158
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff816b9300-ffffffff816b941f: acpi_add_nondev_subnodes (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff8169b3c8)
Location: drivers/acpi/property.c:158
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff81711268)
Location: drivers/acpi/property.c:158
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff8184000b)
Location: drivers/acpi/property.c:158
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff819765fb)
Location: drivers/acpi/property.c:163
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff819bcf6b)
Location: drivers/acpi/property.c:163
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffffffff81a07e1b)
Location: drivers/acpi/property.c:167
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
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
In drivers/acpi/property.c (ffff80001077b33c)
Location: drivers/acpi/property.c:155
Inline: True
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
In drivers/acpi/property.c (ffffffff815defbc)
Location: drivers/acpi/property.c:155
Inline: True
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
In drivers/acpi/property.c (ffffffff815ca5fc)
Location: drivers/acpi/property.c:155
Inline: True
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
In drivers/acpi/property.c (ffffffff815e460c)
Location: drivers/acpi/property.c:155
Inline: True
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
In drivers/acpi/property.c (ffffffff815fe4cc)
Location: drivers/acpi/property.c:155
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
