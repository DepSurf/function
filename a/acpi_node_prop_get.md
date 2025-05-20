# Function: <code>acpi_node_prop_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_node_prop_get(struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148ae75)
Location: drivers/acpi/property.c:419
Inline: False
```
**Symbols:**

```
ffffffff8148ae75-ffffffff8148aea1: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_node_prop_get(struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d9c8b)
Location: drivers/acpi/property.c:419
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_present
```
**Symbols:**

```
ffffffff814d9c8b-ffffffff814d9cb7: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_node_prop_get(struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fc537)
Location: drivers/acpi/property.c:472
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_present
```
**Symbols:**

```
ffffffff814fc537-ffffffff814fc563: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150bd6d)
Location: drivers/acpi/property.c:488
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff8150c5a0-ffffffff8150c5cc: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154dd3d)
Location: drivers/acpi/property.c:494
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff8154f1a0-ffffffff8154f1cc: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815851a5)
Location: drivers/acpi/property.c:494
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff81585a40-ffffffff81585a6c: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159d075)
Location: drivers/acpi/property.c:550
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff8159dfc0-ffffffff8159dfec: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cdf25)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff815cf4e0-ffffffff815cf50e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef1a5)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff815f0760-ffffffff815f078e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c045)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff8169c9e0-ffffffff8169ca0e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8e9e)
Location: drivers/acpi/property.c:557
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff816b9880-ffffffff816b98ae: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169aebe)
Location: drivers/acpi/property.c:557
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff8169b840-ffffffff8169b86e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710d1e)
Location: drivers/acpi/property.c:557
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff817116e0-ffffffff8171170e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff818401c5)
Location: drivers/acpi/property.c:564
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff81840720-ffffffff8184078e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81976765)
Location: drivers/acpi/property.c:723
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff819770f0-ffffffff8197715e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bd0d5)
Location: drivers/acpi/property.c:723
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff819bd9f0-ffffffff819bda5e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a07235)
Location: drivers/acpi/property.c:727
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff81a082c0-ffffffff81a0832e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff800010779c1c)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffff80001077b760-ffff80001077b7ac: acpi_node_prop_get (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815dde35)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff815df3f0-ffffffff815df41e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9475)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff815caa30-ffffffff815caa5e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3485)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff815e4a40-ffffffff815e4a6e: acpi_node_prop_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle *fwnode, const char *propname, void **valptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd345)
Location: drivers/acpi/property.c:554
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
```
**Symbols:**

```
ffffffff815fe900-ffffffff815fe92e: acpi_node_prop_get (STB_GLOBAL)
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
