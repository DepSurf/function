# Function: <code>__devm_create_dev_dax</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81740170)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffffffff81740170-ffffffff81740314: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81764370)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffffffff81764370-ffffffff81764514: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818244c0)
Location: drivers/dax/bus.c:400
Inline: False
```
**Symbols:**

```
ffffffff818244c0-ffffffff818246b9: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff8000109641f8)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffff8000109641f8-ffff8000109643d0: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3ac2c)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
c0a3ac2c-c0a3ada4: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1b240)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
c000000000a1b240-c000000000a1b46c: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d1596)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffffffe0005d1596-ffffffe0005d1708: __devm_create_dev_dax (STB_GLOBAL)
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
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81718a60)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffffffff81718a60-ffffffff81718c04: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f0f90)
Location: drivers/dax/bus.c:387
Inline: False
Direct callers:
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816f0f90-ffffffff816f1134: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81757830)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffffffff81757830-ffffffff817579d4: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dev_dax *__devm_create_dev_dax(struct dax_region *dax_region, int id, struct dev_pagemap *pgmap, enum dev_dax_subsys subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772cd0)
Location: drivers/dax/bus.c:387
Inline: False
```
**Symbols:**

```
ffffffff81772cd0-ffffffff81772e74: __devm_create_dev_dax (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
