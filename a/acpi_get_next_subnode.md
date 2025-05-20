# Function: <code>acpi_get_next_subnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148af1f)
Location: drivers/acpi/property.c:800
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff8148af1f-ffffffff8148afc6: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d9d35)
Location: drivers/acpi/property.c:800
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff814d9d35-ffffffff814d9e00: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fc5e1)
Location: drivers/acpi/property.c:872
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff814fc5e1-ffffffff814fc6ac: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150b1f0)
Location: drivers/acpi/property.c:900
Inline: False
```
**Symbols:**

```
ffffffff8150b1f0-ffffffff8150b34a: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154dd60)
Location: drivers/acpi/property.c:908
Inline: False
```
**Symbols:**

```
ffffffff8154dd60-ffffffff8154defa: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815843f0)
Location: drivers/acpi/property.c:908
Inline: False
```
**Symbols:**

```
ffffffff815843f0-ffffffff815845bf: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159c520)
Location: drivers/acpi/property.c:996
Inline: False
```
**Symbols:**

```
ffffffff8159c520-ffffffff8159c729: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cdc50)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff815cdc50-ffffffff815cddfc: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815eeed0)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff815eeed0-ffffffff815ef074: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b110)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff8169b110-ffffffff8169b2b1: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b7f50)
Location: drivers/acpi/property.c:1029
Inline: False
```
**Symbols:**

```
ffffffff816b7f50-ffffffff816b80fa: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81699ef0)
Location: drivers/acpi/property.c:1009
Inline: False
```
**Symbols:**

```
ffffffff81699ef0-ffffffff8169a094: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8170fd90)
Location: drivers/acpi/property.c:1009
Inline: False
```
**Symbols:**

```
ffffffff8170fd90-ffffffff8170ff34: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183e900)
Location: drivers/acpi/property.c:1020
Inline: False
```
**Symbols:**

```
ffffffff8183e900-ffffffff8183eacb: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81975410)
Location: drivers/acpi/property.c:1203
Inline: False
```
**Symbols:**

```
ffffffff81975410-ffffffff819755b3: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bbc50)
Location: drivers/acpi/property.c:1191
Inline: False
```
**Symbols:**

```
ffffffff819bbc50-ffffffff819bbe24: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a06500)
Location: drivers/acpi/property.c:1259
Inline: False
```
**Symbols:**

```
ffffffff81a06500-ffffffff81a066d4: acpi_get_next_subnode (STB_GLOBAL)
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
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff800010779c48)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffff800010779c48-ffff800010779e00: acpi_get_next_subnode (STB_GLOBAL)
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
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ddb60)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff815ddb60-ffffffff815ddd04: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c91a0)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff815c91a0-ffffffff815c9344: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e31b0)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff815e31b0-ffffffff815e3354: acpi_get_next_subnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *acpi_get_next_subnode(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd070)
Location: drivers/acpi/property.c:1014
Inline: False
```
**Symbols:**

```
ffffffff815fd070-ffffffff815fd214: acpi_get_next_subnode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_handle *fwnode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
</li>
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
