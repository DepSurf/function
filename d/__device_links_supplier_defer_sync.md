# Function: <code>__device_links_supplier_defer_sync</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __device_links_supplier_defer_sync(struct device *sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3150)
Location: drivers/base/core.c:840
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff817b3150-ffffffff817b31ba: __device_links_supplier_defer_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __device_links_supplier_defer_sync(struct device *sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7a10)
Location: drivers/base/core.c:1101
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff817c7a10-ffffffff817c7a7a: __device_links_supplier_defer_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __device_links_supplier_defer_sync(struct device *sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aaf20)
Location: drivers/base/core.c:1138
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff817aaf20-ffffffff817aaf8a: __device_links_supplier_defer_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __device_links_supplier_defer_sync(struct device *sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81834050)
Location: drivers/base/core.c:1153
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81834050-ffffffff818340ba: __device_links_supplier_defer_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __device_links_supplier_defer_sync(struct device *sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975960)
Location: drivers/base/core.c:1165
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81975960-ffffffff819759e8: __device_links_supplier_defer_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __device_links_supplier_defer_sync(struct device *sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae17d0)
Location: drivers/base/core.c:1272
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81ae17d0-ffffffff81ae1858: __device_links_supplier_defer_sync (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81b34940)
Location: drivers/base/core.c:1211
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
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
In drivers/base/core.c (ffffffff81b8c370)
Location: drivers/base/core.c:1214
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
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
</ul>
