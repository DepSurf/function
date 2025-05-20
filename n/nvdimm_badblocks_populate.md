# Function: <code>nvdimm_badblocks_populate</code>

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
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ebda0)
Location: drivers/nvdimm/core.c:530
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff815ebda0-ffffffff815ebeea: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81618990)
Location: drivers/nvdimm/core.c:501
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81618990-ffffffff81618ada: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162c830)
Location: drivers/nvdimm/core.c:502
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8162c830-ffffffff8162c977: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816a23f0)
Location: drivers/nvdimm/badrange.c:277
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff816a23f0-ffffffff816a2537: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816de580)
Location: drivers/nvdimm/badrange.c:277
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff816de580-ffffffff816de6ba: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81700940)
Location: drivers/nvdimm/badrange.c:277
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81700940-ffffffff81700a7a: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8173a7b0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8173a7b0-ffffffff8173a8ee: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8175e480)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8175e480-ffffffff8175e5be: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8181e040)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8181e040-ffffffff8181e0eb: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8182cfc0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8182cfc0-ffffffff8182d06b: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81810250)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81810250-ffffffff8181038c: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81d0b506-ffffffff81d0b51a: nvdimm_badblocks_populate.cold (STB_LOCAL)
ffffffff8189a870-ffffffff8189a9b9: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81ed43cd-ffffffff81ed43e2: nvdimm_badblocks_populate.cold (STB_LOCAL)
ffffffff819e3fa0-ffffffff819e40fc: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8209b443-ffffffff8209b458: nvdimm_badblocks_populate.cold (STB_LOCAL)
ffffffff81b5fc90-ffffffff81b5fdec: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8211c312-ffffffff8211c327: nvdimm_badblocks_populate.cold (STB_LOCAL)
ffffffff81bb3230-ffffffff81bb338c: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff821fa199-ffffffff821fa1ae: nvdimm_badblocks_populate.cold (STB_LOCAL)
ffffffff81c07720-ffffffff81c0787c: nvdimm_badblocks_populate (STB_GLOBAL)
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
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffff80001095fb88)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffff80001095fb88-ffff80001095fce4: nvdimm_badblocks_populate (STB_GLOBAL)
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
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (c000000000a126e0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
c000000000a126e0-c000000000a128a8: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffe0005cd77e)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffe0005cd77e-ffffffe0005cd8aa: nvdimm_badblocks_populate (STB_GLOBAL)
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
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81712b70)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81712b70-ffffffff81712cae: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816e65f0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
**Symbols:**

```
ffffffff816e65f0-ffffffff816e672e: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81751940)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81751940-ffffffff81751a7e: nvdimm_badblocks_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvdimm_badblocks_populate(struct nd_region *nd_region, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8176cea0)
Location: drivers/nvdimm/badrange.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8176cea0-ffffffff8176cfde: nvdimm_badblocks_populate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct range *range</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct resource *res</code>
</li>
</ul>
</details>
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
