# Function: <code>generic_nvdimm_flush</code>

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
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81732700)
Location: drivers/nvdimm/region_devs.c:1148
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffff81732700-ffffffff817327ab: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817565b0)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffff817565b0-ffffffff8175665b: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81815b90)
Location: drivers/nvdimm/region_devs.c:1196
Inline: False
```
**Symbols:**

```
ffffffff81815b90-ffffffff81815c3b: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81824d80)
Location: drivers/nvdimm/region_devs.c:1196
Inline: False
```
**Symbols:**

```
ffffffff81824d80-ffffffff81824e2b: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81808110)
Location: drivers/nvdimm/region_devs.c:1203
Inline: False
```
**Symbols:**

```
ffffffff81808110-ffffffff818081b9: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1203
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
**Symbols:**

```
ffffffff81d0b12c-ffffffff81d0b189: generic_nvdimm_flush.cold (STB_LOCAL)
ffffffff818928a0-ffffffff81892971: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1088
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
**Symbols:**

```
ffffffff81ed35a9-ffffffff81ed3606: generic_nvdimm_flush.cold (STB_LOCAL)
ffffffff819dca30-ffffffff819dcb10: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1146
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
**Symbols:**

```
ffffffff8209a813-ffffffff8209a870: generic_nvdimm_flush.cold (STB_LOCAL)
ffffffff81b580c0-ffffffff81b581a0: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1146
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
**Symbols:**

```
ffffffff8211b8b1-ffffffff8211b90a: generic_nvdimm_flush.cold (STB_LOCAL)
ffffffff81bab630-ffffffff81bab710: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1147
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
**Symbols:**

```
ffffffff821f9738-ffffffff821f9791: generic_nvdimm_flush.cold (STB_LOCAL)
ffffffff81bff970-ffffffff81bffa50: generic_nvdimm_flush (STB_GLOBAL)
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
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010957a08)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffff800010957a08-ffff800010957ae4: generic_nvdimm_flush (STB_GLOBAL)
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
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a05c60)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
c000000000a05c60-c000000000a05d84: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c6942)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffe0005c6942-ffffffe0005c6a46: generic_nvdimm_flush (STB_GLOBAL)
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
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170aca0)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffff8170aca0-ffffffff8170ad4b: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816de720)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffff816de720-ffffffff816de7cb: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81749a70)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffff81749a70-ffffffff81749b1b: generic_nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81764ef0)
Location: drivers/nvdimm/region_devs.c:1099
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
**Symbols:**

```
ffffffff81764ef0-ffffffff81764f9b: generic_nvdimm_flush (STB_GLOBAL)
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
