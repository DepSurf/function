# Function: <code>memregion_alloc</code>

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
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff815e3f30)
Location: lib/memregion.c:8
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
**Symbols:**

```
ffffffff815e3f30-ffffffff815e3f4b: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff81608460)
Location: lib/memregion.c:9
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff81608460-ffffffff8160847b: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff815eb0c0)
Location: lib/memregion.c:9
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff815eb0c0-ffffffff815eb0db: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff816575c0)
Location: lib/memregion.c:9
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff816575c0-ffffffff816575db: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff8176eec0)
Location: lib/memregion.c:9
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff8176eec0-ffffffff8176eee7: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff8189e830)
Location: lib/memregion.c:9
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff8189e830-ffffffff8189e857: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff818e0e00)
Location: lib/memregion.c:9
Inline: False
```
**Symbols:**

```
ffffffff818e0e00-ffffffff818e0e27: memregion_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memregion_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/memregion.c (ffffffff81927970)
Location: lib/memregion.c:9
Inline: False
```
**Symbols:**

```
ffffffff81927970-ffffffff81927997: memregion_alloc (STB_GLOBAL)
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
