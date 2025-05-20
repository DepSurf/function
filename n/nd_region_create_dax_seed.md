# Function: <code>nd_region_create_dax_seed</code>

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
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3ee0)
Location: drivers/nvdimm/namespace_devs.c:1787
Inline: False
```
**Symbols:**

```
ffffffff815f3ee0-ffffffff815f3f32: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81621880)
Location: drivers/nvdimm/namespace_devs.c:1929
Inline: False
```
**Symbols:**

```
ffffffff81621880-ffffffff816218d2: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816362e0)
Location: drivers/nvdimm/namespace_devs.c:2106
Inline: False
```
**Symbols:**

```
ffffffff816362e0-ffffffff81636323: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169f5d0)
Location: drivers/nvdimm/namespace_devs.c:2115
Inline: False
```
**Symbols:**

```
ffffffff8169f5d0-ffffffff8169f613: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816db8d0)
Location: drivers/nvdimm/namespace_devs.c:2109
Inline: False
```
**Symbols:**

```
ffffffff816db8d0-ffffffff816db913: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd8d0)
Location: drivers/nvdimm/namespace_devs.c:2134
Inline: False
```
**Symbols:**

```
ffffffff816fd8d0-ffffffff816fd913: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
```
**Symbols:**

```
ffffffff81737adb-ffffffff81737b02: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff81737480-ffffffff817374b8: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8175b809-ffffffff8175b81d: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff8175b230-ffffffff8175b268: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2182
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8181b084-ffffffff8181b098: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff8181ac20-ffffffff8181ac5a: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2182
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c15c73-ffffffff81c15c87: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff81829d40-ffffffff81829d7a: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2182
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c079cc-ffffffff81c079e0: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff8180d020-ffffffff8180d05a: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2175
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81d0b2ea-ffffffff81d0b2fe: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff81897590-ffffffff818975ca: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1858
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81ed3c66-ffffffff81ed3c7a: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff819e1270-ffffffff819e12b2: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5cd80)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81b5cd80-ffffffff81b5cddd: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bb0330)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81bb0330-ffffffff81bb038d: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04790)
Location: drivers/nvdimm/namespace_devs.c:1859
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c04790-ffffffff81c047ed: nd_region_create_dax_seed (STB_GLOBAL)
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
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095c8c0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
```
**Symbols:**

```
ffff80001095c8c0-ffff80001095c90c: nd_region_create_dax_seed (STB_GLOBAL)
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
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0de80)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
c000000000a0de80-c000000000a0defc: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cac4c)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
```
**Symbols:**

```
ffffffe0005cac4c-ffffffe0005cac90: nd_region_create_dax_seed (STB_GLOBAL)
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
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8170fef9-ffffffff8170ff0d: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff8170f920-ffffffff8170f958: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff816e3979-ffffffff816e398d: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff816e33a0-ffffffff816e33d8: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8174ecc9-ffffffff8174ecdd: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff8174e6f0-ffffffff8174e728: nd_region_create_dax_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void nd_region_create_dax_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2141
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8176a149-ffffffff8176a15d: nd_region_create_dax_seed.cold (STB_LOCAL)
ffffffff81769b70-ffffffff81769ba8: nd_region_create_dax_seed (STB_GLOBAL)
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
