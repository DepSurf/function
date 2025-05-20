# Function: <code>nd_region_create_btt_seed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159df30)
Location: drivers/nvdimm/namespace_devs.c:1745
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
```
**Symbols:**

```
ffffffff8159df30-ffffffff8159df82: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3fa0)
Location: drivers/nvdimm/namespace_devs.c:1811
Inline: False
```
**Symbols:**

```
ffffffff815f3fa0-ffffffff815f3ff2: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81621940)
Location: drivers/nvdimm/namespace_devs.c:1953
Inline: False
```
**Symbols:**

```
ffffffff81621940-ffffffff81621992: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81636380)
Location: drivers/nvdimm/namespace_devs.c:2130
Inline: False
```
**Symbols:**

```
ffffffff81636380-ffffffff816363c3: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169f670)
Location: drivers/nvdimm/namespace_devs.c:2139
Inline: False
```
**Symbols:**

```
ffffffff8169f670-ffffffff8169f6b3: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816db970)
Location: drivers/nvdimm/namespace_devs.c:2133
Inline: False
```
**Symbols:**

```
ffffffff816db970-ffffffff816db9b3: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd970)
Location: drivers/nvdimm/namespace_devs.c:2158
Inline: False
```
**Symbols:**

```
ffffffff816fd970-ffffffff816fd9b3: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
```
**Symbols:**

```
ffffffff81737b29-ffffffff81737b50: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff81737500-ffffffff81737538: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8175b831-ffffffff8175b845: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff8175b2b0-ffffffff8175b2e8: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2206
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8181b0ac-ffffffff8181b0c0: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff8181aca0-ffffffff8181acda: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2206
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c15c9b-ffffffff81c15caf: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff81829dc0-ffffffff81829dfa: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2206
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c079f4-ffffffff81c07a08: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff8180d0a0-ffffffff8180d0da: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2199
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81d0b312-ffffffff81d0b326: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff81897610-ffffffff8189764a: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1882
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81ed3c8e-ffffffff81ed3ca2: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff819e1310-ffffffff819e1352: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5ce60)
Location: drivers/nvdimm/namespace_devs.c:1872
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81b5ce60-ffffffff81b5cebd: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bb0410)
Location: drivers/nvdimm/namespace_devs.c:1872
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81bb0410-ffffffff81bb046d: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04870)
Location: drivers/nvdimm/namespace_devs.c:1883
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff81c04870-ffffffff81c048cd: nd_region_create_btt_seed (STB_GLOBAL)
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
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095c960)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffff80001095c960-ffff80001095c9c0: nd_region_create_btt_seed (STB_GLOBAL)
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
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0df80)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
c000000000a0df80-c000000000a0dffc: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cacd4)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffe0005cacd4-ffffffe0005cad28: nd_region_create_btt_seed (STB_GLOBAL)
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
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8170ff21-ffffffff8170ff35: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff8170f9a0-ffffffff8170f9d8: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff816e39a1-ffffffff816e39b5: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff816e3420-ffffffff816e3458: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8174ecf1-ffffffff8174ed05: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff8174e770-ffffffff8174e7a8: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void nd_region_create_btt_seed(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2165
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
```
**Symbols:**

```
ffffffff8176a171-ffffffff8176a185: nd_region_create_btt_seed.cold (STB_LOCAL)
ffffffff81769bf0-ffffffff81769c28: nd_region_create_btt_seed (STB_GLOBAL)
```
</details>
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
