# Function: <code>nd_region_create_ns_seed</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81621680)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
```
**Symbols:**

```
ffffffff81621680-ffffffff81621873: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816360b0)
Location: drivers/nvdimm/namespace_devs.c:2083
Inline: False
```
**Symbols:**

```
ffffffff816360b0-ffffffff816362d8: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169f3a0)
Location: drivers/nvdimm/namespace_devs.c:2092
Inline: False
```
**Symbols:**

```
ffffffff8169f3a0-ffffffff8169f5c8: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816db6b0)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: False
```
**Symbols:**

```
ffffffff816db6b0-ffffffff816db8c6: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd6a0)
Location: drivers/nvdimm/namespace_devs.c:2111
Inline: False
```
**Symbols:**

```
ffffffff816fd6a0-ffffffff816fd8c1: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
```
**Symbols:**

```
ffffffff81737ac8-ffffffff81737adb: nd_region_create_ns_seed.cold (STB_LOCAL)
ffffffff81737260-ffffffff81737478: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8175b010)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8175b010-ffffffff8175b22f: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8181aae0)
Location: drivers/nvdimm/namespace_devs.c:2159
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8181aae0-ffffffff8181ac14: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81829c00)
Location: drivers/nvdimm/namespace_devs.c:2159
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81829c00-ffffffff81829d34: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180ce10)
Location: drivers/nvdimm/namespace_devs.c:2159
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8180ce10-ffffffff8180d011: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81897380)
Location: drivers/nvdimm/namespace_devs.c:2152
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81897380-ffffffff81897581: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819e1100)
Location: drivers/nvdimm/namespace_devs.c:1835
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff819e1100-ffffffff819e1266: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5cbf0)
Location: drivers/nvdimm/namespace_devs.c:1825
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81b5cbf0-ffffffff81b5cd69: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bb01a0)
Location: drivers/nvdimm/namespace_devs.c:1825
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81bb01a0-ffffffff81bb0319: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c045d0)
Location: drivers/nvdimm/namespace_devs.c:1836
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c045d0-ffffffff81c04778: nd_region_create_ns_seed (STB_GLOBAL)
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
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095c678)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffff80001095c678-ffff80001095c8c0: nd_region_create_ns_seed (STB_GLOBAL)
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
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0dbb0)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
c000000000a0dbb0-c000000000a0de7c: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005caa66)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffe0005caa66-ffffffe0005cac4c: nd_region_create_ns_seed (STB_GLOBAL)
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
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f700)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8170f700-ffffffff8170f91f: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e3180)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff816e3180-ffffffff816e339f: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174e4d0)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8174e4d0-ffffffff8174e6ef: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nd_region_create_ns_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81769950)
Location: drivers/nvdimm/namespace_devs.c:2118
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81769950-ffffffff81769b6f: nd_region_create_ns_seed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
