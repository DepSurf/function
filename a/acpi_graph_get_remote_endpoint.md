# Function: <code>acpi_graph_get_remote_endpoint</code>

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
int acpi_graph_get_remote_endpoint(struct fwnode_handle *fwnode, struct fwnode_handle **parent, struct fwnode_handle **port, struct fwnode_handle **endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150c7a0)
Location: drivers/acpi/property.c:1072
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8150c7a0-ffffffff8150c890: acpi_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode, struct fwnode_handle **parent, struct fwnode_handle **port, struct fwnode_handle **endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154f3a0)
Location: drivers/acpi/property.c:1085
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8154f3a0-ffffffff8154f490: acpi_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode, struct fwnode_handle **parent, struct fwnode_handle **port, struct fwnode_handle **endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81585c30)
Location: drivers/acpi/property.c:1085
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff81585c30-ffffffff81585d1b: acpi_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159cfb0)
Location: drivers/acpi/property.c:1200
Inline: False
```
**Symbols:**

```
ffffffff8159cfb0-ffffffff8159d06f: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce510)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff815ce510-ffffffff815ce5cf: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef790)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff815ef790-ffffffff815ef84f: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b9a0)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff8169b9a0-ffffffff8169ba5e: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b87c0)
Location: drivers/acpi/property.c:1241
Inline: False
```
**Symbols:**

```
ffffffff816b87c0-ffffffff816b887e: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a760)
Location: drivers/acpi/property.c:1220
Inline: False
```
**Symbols:**

```
ffffffff8169a760-ffffffff8169a820: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff817105c0)
Location: drivers/acpi/property.c:1215
Inline: False
```
**Symbols:**

```
ffffffff817105c0-ffffffff81710680: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183f5f0)
Location: drivers/acpi/property.c:1224
Inline: False
```
**Symbols:**

```
ffffffff8183f5f0-ffffffff8183f6bf: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81975e60)
Location: drivers/acpi/property.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81975e60-ffffffff81975f2f: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bc740)
Location: drivers/acpi/property.c:1383
Inline: False
```
**Symbols:**

```
ffffffff819bc740-ffffffff819bc80f: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a07030)
Location: drivers/acpi/property.c:1451
Inline: False
```
**Symbols:**

```
ffffffff81a07030-ffffffff81a070ff: acpi_graph_get_remote_endpoint (STB_LOCAL)
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
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a510)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffff80001077a510-ffff80001077a5f4: acpi_graph_get_remote_endpoint (STB_LOCAL)
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
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de420)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff815de420-ffffffff815de4df: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9a60)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff815c9a60-ffffffff815c9b1f: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3a70)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff815e3a70-ffffffff815e3b2f: acpi_graph_get_remote_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *acpi_graph_get_remote_endpoint(const struct fwnode_handle *__fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd930)
Location: drivers/acpi/property.c:1226
Inline: False
```
**Symbols:**

```
ffffffff815fd930-ffffffff815fd9ef: acpi_graph_get_remote_endpoint (STB_LOCAL)
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
<b>Param added. </b>
<code>const struct fwnode_handle *__fwnode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle **parent</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle **port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle **endpoint</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct fwnode_handle *</code>
</li>
</ul>
</details>
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
