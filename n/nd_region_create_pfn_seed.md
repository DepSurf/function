# Function: <code>nd_region_create_pfn_seed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3f40)
Location: drivers/nvdimm/namespace_devs.c:1799
Inline: False
```
**Symbols:**

```
ffffffff815f3f40-ffffffff815f3f92: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816218e0)
Location: drivers/nvdimm/namespace_devs.c:1941
Inline: False
```
**Symbols:**

```
ffffffff816218e0-ffffffff81621932: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81636330)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
```
**Symbols:**

```
ffffffff81636330-ffffffff81636373: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169f620)
Location: drivers/nvdimm/namespace_devs.c:2127
Inline: False
```
**Symbols:**

```
ffffffff8169f620-ffffffff8169f663: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816db920)
Location: drivers/nvdimm/namespace_devs.c:2121
Inline: False
```
**Symbols:**

```
ffffffff816db920-ffffffff816db963: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd920)
Location: drivers/nvdimm/namespace_devs.c:2146
Inline: False
```
**Symbols:**

```
ffffffff816fd920-ffffffff816fd963: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81737b02-ffffffff81737b29: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff817374c0-ffffffff817374f8: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8175b81d-ffffffff8175b831: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff8175b270-ffffffff8175b2a8: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2194
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8181b098-ffffffff8181b0ac: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff8181ac60-ffffffff8181ac9a: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2194
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c15c87-ffffffff81c15c9b: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff81829d80-ffffffff81829dba: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2194
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c079e0-ffffffff81c079f4: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff8180d060-ffffffff8180d09a: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2187
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81d0b2fe-ffffffff81d0b312: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff818975d0-ffffffff8189760a: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1870
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81ed3c7a-ffffffff81ed3c8e: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff819e12c0-ffffffff819e1302: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5cdf0)
Location: drivers/nvdimm/namespace_devs.c:1860
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81b5cdf0-ffffffff81b5ce4d: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bb03a0)
Location: drivers/nvdimm/namespace_devs.c:1860
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81bb03a0-ffffffff81bb03fd: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04800)
Location: drivers/nvdimm/namespace_devs.c:1871
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c04800-ffffffff81c0485d: nd_region_create_pfn_seed (STB_GLOBAL)
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
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095c910)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
```
**Symbols:**

```
ffff80001095c910-ffff80001095c95c: nd_region_create_pfn_seed (STB_GLOBAL)
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
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0df00)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
c000000000a0df00-c000000000a0df7c: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cac90)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
```
**Symbols:**

```
ffffffe0005cac90-ffffffe0005cacd4: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8170ff0d-ffffffff8170ff21: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff8170f960-ffffffff8170f998: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff816e398d-ffffffff816e39a1: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff816e33e0-ffffffff816e3418: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8174ecdd-ffffffff8174ecf1: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff8174e730-ffffffff8174e768: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void nd_region_create_pfn_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8176a15d-ffffffff8176a171: nd_region_create_pfn_seed.cold (STB_LOCAL)
ffffffff81769bb0-ffffffff81769be8: nd_region_create_pfn_seed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
