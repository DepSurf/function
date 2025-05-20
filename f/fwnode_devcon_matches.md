# Function: <code>fwnode_devcon_matches</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int fwnode_devcon_matches(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986f20)
Location: drivers/base/property.c:1243
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81986f20-ffffffff81987099: fwnode_devcon_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int fwnode_devcon_matches(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5760)
Location: drivers/base/property.c:1257
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81af5760-ffffffff81af58d9: fwnode_devcon_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int fwnode_devcon_matches(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43990)
Location: drivers/base/property.c:1318
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81b43990-ffffffff81b43b3b: fwnode_devcon_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int fwnode_devcon_matches(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b9e0)
Location: drivers/base/property.c:1382
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81b9b9e0-ffffffff81b9bb8b: fwnode_devcon_matches (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
