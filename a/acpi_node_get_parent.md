# Function: <code>acpi_node_get_parent</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150be50)
Location: drivers/acpi/property.c:966
Inline: True
```
**Symbols:**

```
ffffffff8150be50-ffffffff8150bed0: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e250)
Location: drivers/acpi/property.c:978
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff8154e250-ffffffff8154e2d8: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81585290)
Location: drivers/acpi/property.c:978
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff81585290-ffffffff81585318: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159d510)
Location: drivers/acpi/property.c:1066
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff8159d510-ffffffff8159d598: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce000)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff815ce000-ffffffff815ce088: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef280)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff815ef280-ffffffff815ef308: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b490)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff8169b490-ffffffff8169b518: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b82f0)
Location: drivers/acpi/property.c:1107
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff816b82f0-ffffffff816b8378: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a290)
Location: drivers/acpi/property.c:1087
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff8169a290-ffffffff8169a318: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8170ff40)
Location: drivers/acpi/property.c:1087
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff8170ff40-ffffffff8170ff8c: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff818400d5)
Location: drivers/acpi/property.c:1095
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff8183f6c0-ffffffff8183f724: acpi_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819766d5)
Location: drivers/acpi/property.c:1265
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff81975f40-ffffffff81975fb1: acpi_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bc8b5)
Location: drivers/acpi/property.c:1253
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff819bc820-ffffffff819bc891: acpi_node_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a071a5)
Location: drivers/acpi/property.c:1321
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff81a07110-ffffffff81a07181: acpi_node_get_parent (STB_LOCAL)
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
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff800010779ec0)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffff800010779ec0-ffff800010779f70: acpi_node_get_parent (STB_GLOBAL)
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
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ddf10)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff815ddf10-ffffffff815ddf98: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9550)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff815c9550-ffffffff815c95d8: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3560)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff815e3560-ffffffff815e35e8: acpi_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *acpi_node_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd420)
Location: drivers/acpi/property.c:1092
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
```
**Symbols:**

```
ffffffff815fd420-ffffffff815fd4a8: acpi_node_get_parent (STB_GLOBAL)
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
