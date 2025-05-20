# Function: <code>nd_pfn_clear_memmap_errors</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81702b5f)
Location: drivers/nvdimm/pfn_devs.c:370
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8173ca0d)
Location: drivers/nvdimm/pfn_devs.c:362
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817607b0)
Location: drivers/nvdimm/pfn_devs.c:368
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:360
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81820590-ffffffff81820773: nd_pfn_clear_memmap_errors (STB_LOCAL)
ffffffff81821092-ffffffff818210b4: nd_pfn_clear_memmap_errors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:360
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff8182f480-ffffffff8182f663: nd_pfn_clear_memmap_errors (STB_LOCAL)
ffffffff81c15fe6-ffffffff81c16008: nd_pfn_clear_memmap_errors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:360
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff818125b0-ffffffff81812790: nd_pfn_clear_memmap_errors (STB_LOCAL)
ffffffff81c07d37-ffffffff81c07d59: nd_pfn_clear_memmap_errors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:360
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff8189cc40-ffffffff8189ce20: nd_pfn_clear_memmap_errors (STB_LOCAL)
ffffffff81d0b6f2-ffffffff81d0b714: nd_pfn_clear_memmap_errors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:362
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff819e6510-ffffffff819e672b: nd_pfn_clear_memmap_errors (STB_LOCAL)
ffffffff81ed4576-ffffffff81ed4598: nd_pfn_clear_memmap_errors.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81b62590)
Location: drivers/nvdimm/pfn_devs.c:364
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81b62590-ffffffff81b627c0: nd_pfn_clear_memmap_errors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5b90)
Location: drivers/nvdimm/pfn_devs.c:364
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81bb5b90-ffffffff81bb5d9d: nd_pfn_clear_memmap_errors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nd_pfn_clear_memmap_errors(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a170)
Location: drivers/nvdimm/pfn_devs.c:364
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81c0a170-ffffffff81c0a37d: nd_pfn_clear_memmap_errors (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a15c58)
Location: drivers/nvdimm/pfn_devs.c:368
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81714ea0)
Location: drivers/nvdimm/pfn_devs.c:368
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8920)
Location: drivers/nvdimm/pfn_devs.c:368
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81753c70)
Location: drivers/nvdimm/pfn_devs.c:368
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f0e0)
Location: drivers/nvdimm/pfn_devs.c:368
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
</details>
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
