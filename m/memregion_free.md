# Function: <code>memregion_free</code>

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
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff815e3f50)
Location: lib/memregion.c:14
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_release
```
**Symbols:**

```
ffffffff815e3f50-ffffffff815e3f64: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff81608480)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff81608480-ffffffff81608494: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff815eb0e0)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff815eb0e0-ffffffff815eb0f4: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff816575e0)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff816575e0-ffffffff816575f4: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff8176eef0)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff8176eef0-ffffffff8176ef0c: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff8189e870)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff8189e870-ffffffff8189e88c: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff818e0e40)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_release
```
**Symbols:**

```
ffffffff818e0e40-ffffffff818e0e5c: memregion_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memregion_free(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff819279b0)
Location: lib/memregion.c:15
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_release
```
**Symbols:**

```
ffffffff819279b0-ffffffff819279cc: memregion_free (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
