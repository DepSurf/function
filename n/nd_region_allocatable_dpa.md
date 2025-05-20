# Function: <code>nd_region_allocatable_dpa</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d6b80)
Location: drivers/nvdimm/region_devs.c:392
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff816d6b80-ffffffff816d6c8e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f8960)
Location: drivers/nvdimm/region_devs.c:397
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff816f8960-ffffffff816f8a6e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81732ad1-ffffffff81732ae4: nd_region_allocatable_dpa.cold (STB_LOCAL)
ffffffff81732030-ffffffff81732137: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817561b0)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff817561b0-ffffffff817562be: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81815730)
Location: drivers/nvdimm/region_devs.c:365
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81815730-ffffffff8181583e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81824920)
Location: drivers/nvdimm/region_devs.c:365
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81824920-ffffffff81824a2e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81807cb0)
Location: drivers/nvdimm/region_devs.c:365
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81807cb0-ffffffff81807dbe: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81892450)
Location: drivers/nvdimm/region_devs.c:365
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81892450-ffffffff8189255e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819dc690)
Location: drivers/nvdimm/region_devs.c:329
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff819dc690-ffffffff819dc73a: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b57ca0)
Location: drivers/nvdimm/region_devs.c:376
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81b57ca0-ffffffff81b57d4a: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bab210)
Location: drivers/nvdimm/region_devs.c:376
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81bab210-ffffffff81bab2ba: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bff550)
Location: drivers/nvdimm/region_devs.c:377
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81bff550-ffffffff81bff5fa: nd_region_allocatable_dpa (STB_GLOBAL)
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
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff8000109575a0)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffff8000109575a0-ffff8000109576e0: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a055d0)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
c000000000a055d0-c000000000a05798: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c65a2)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffe0005c65a2-ffffffe0005c669a: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170a8a0)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff8170a8a0-ffffffff8170a9ae: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816de320)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff816de320-ffffffff816de42e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81749670)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81749670-ffffffff8174977e: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
resource_size_t nd_region_allocatable_dpa(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81764af0)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81764af0-ffffffff81764bfe: nd_region_allocatable_dpa (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
