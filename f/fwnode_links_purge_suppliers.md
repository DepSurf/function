# Function: <code>fwnode_links_purge_suppliers</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fwnode_links_purge_suppliers(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6380)
Location: drivers/base/core.c:107
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff817c6380-ffffffff817c6427: fwnode_links_purge_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fwnode_links_purge_suppliers(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817a96e0)
Location: drivers/base/core.c:109
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff817a96e0-ffffffff817a9787: fwnode_links_purge_suppliers (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81835d7b)
Location: drivers/base/core.c:127
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
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
In drivers/base/core.c (ffffffff81977ce9)
Location: drivers/base/core.c:128
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
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
In drivers/base/core.c (ffffffff81ae6639)
Location: drivers/base/core.c:151
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
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
In drivers/base/core.c (ffffffff81b34ab2)
Location: drivers/base/core.c:138
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
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
In drivers/base/core.c (ffffffff81b8c4e2)
Location: drivers/base/core.c:139
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:fwnode_links_purge
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
