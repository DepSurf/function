# Function: <code>nd_sector_size_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t nd_sector_size_store(struct device *dev, const char *buf, long unsigned int *current_lbasize, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815973c0)
Location: drivers/nvdimm/core.c:192
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
**Symbols:**

```
ffffffff815973c0-ffffffff8159746b: nd_sector_size_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t nd_sector_size_store(struct device *dev, const char *buf, long unsigned int *current_lbasize, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ec590)
Location: drivers/nvdimm/core.c:295
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
**Symbols:**

```
ffffffff815ec590-ffffffff815ec63a: nd_sector_size_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t nd_sector_size_store(struct device *dev, const char *buf, long unsigned int *current_lbasize, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81619370)
Location: drivers/nvdimm/core.c:295
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
**Symbols:**

```
ffffffff81619370-ffffffff8161941a: nd_sector_size_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t nd_sector_size_store(struct device *dev, const char *buf, long unsigned int *current_lbasize, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162d1b0)
Location: drivers/nvdimm/core.c:295
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
**Symbols:**

```
ffffffff8162d1b0-ffffffff8162d25a: nd_sector_size_store (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
