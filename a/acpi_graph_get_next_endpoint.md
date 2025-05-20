# Function: <code>acpi_graph_get_next_endpoint</code>

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
struct fwnode_handle *acpi_graph_get_next_endpoint(struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150c690)
Location: drivers/acpi/property.c:995
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff8150c690-ffffffff8150c777: acpi_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154f290)
Location: drivers/acpi/property.c:1007
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff8154f290-ffffffff8154f377: acpi_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81585b20)
Location: drivers/acpi/property.c:1007
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81585b20-ffffffff81585c07: acpi_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159cbe0)
Location: drivers/acpi/property.c:1115
Inline: False
```
**Symbols:**

```
ffffffff8159cbe0-ffffffff8159ccc3: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce690)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815ce690-ffffffff815ce764: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef910)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815ef910-ffffffff815ef9e4: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169bb20)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff8169bb20-ffffffff8169bbf4: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8940)
Location: drivers/acpi/property.c:1156
Inline: False
```
**Symbols:**

```
ffffffff816b8940-ffffffff816b8a14: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a8e0)
Location: drivers/acpi/property.c:1136
Inline: False
```
**Symbols:**

```
ffffffff8169a8e0-ffffffff8169a9b4: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710740)
Location: drivers/acpi/property.c:1131
Inline: False
```
**Symbols:**

```
ffffffff81710740-ffffffff81710814: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183f070)
Location: drivers/acpi/property.c:1140
Inline: False
```
**Symbols:**

```
ffffffff8183f070-ffffffff8183f15b: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81975850)
Location: drivers/acpi/property.c:1311
Inline: False
```
**Symbols:**

```
ffffffff81975850-ffffffff8197593b: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bc0c0)
Location: drivers/acpi/property.c:1299
Inline: False
```
**Symbols:**

```
ffffffff819bc0c0-ffffffff819bc1ab: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a06a40)
Location: drivers/acpi/property.c:1367
Inline: False
```
**Symbols:**

```
ffffffff81a06a40-ffffffff81a06b2b: acpi_graph_get_next_endpoint (STB_LOCAL)
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
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a6f8)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffff80001077a6f8-ffff80001077a818: acpi_graph_get_next_endpoint (STB_LOCAL)
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
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de5a0)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815de5a0-ffffffff815de674: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9be0)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815c9be0-ffffffff815c9cb4: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3bf0)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815e3bf0-ffffffff815e3cc4: acpi_graph_get_next_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fdab0)
Location: drivers/acpi/property.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815fdab0-ffffffff815fdb84: acpi_graph_get_next_endpoint (STB_LOCAL)
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
