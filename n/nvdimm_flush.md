# Function: <code>nvdimm_flush</code>

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
void nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815ef290)
Location: drivers/nvdimm/region_devs.c:886
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff815ef290-ffffffff815ef33c: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161c460)
Location: drivers/nvdimm/region_devs.c:934
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8161c460-ffffffff8161c50c: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816304a0)
Location: drivers/nvdimm/region_devs.c:1035
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816304a0-ffffffff8163054c: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81698cd0)
Location: drivers/nvdimm/region_devs.c:1056
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81698cd0-ffffffff81698d7c: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d4f80)
Location: drivers/nvdimm/region_devs.c:1096
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816d4f80-ffffffff816d502c: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvdimm_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f6c80)
Location: drivers/nvdimm/region_devs.c:1124
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816f6c80-ffffffff816f6d2c: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817327b0)
Location: drivers/nvdimm/region_devs.c:1131
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff817327b0-ffffffff817327de: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81756660)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81756660-ffffffff8175668e: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81815c40)
Location: drivers/nvdimm/region_devs.c:1179
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81815c40-ffffffff81815c6e: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81824e30)
Location: drivers/nvdimm/region_devs.c:1179
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81824e30-ffffffff81824e5e: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818081c0)
Location: drivers/nvdimm/region_devs.c:1186
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff818081c0-ffffffff818081ee: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81892a0b)
Location: drivers/nvdimm/region_devs.c:1186
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81892980-ffffffff818929ae: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819dcbbe)
Location: drivers/nvdimm/region_devs.c:1071
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff819dcb10-ffffffff819dcb56: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b5826e)
Location: drivers/nvdimm/region_devs.c:1129
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81b581b0-ffffffff81b581f6: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bab7de)
Location: drivers/nvdimm/region_devs.c:1129
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81bab720-ffffffff81bab766: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bffb1e)
Location: drivers/nvdimm/region_devs.c:1130
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81bffa60-ffffffff81bffaa6: nvdimm_flush (STB_GLOBAL)
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
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010957ae8)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffff800010957ae8-ffff800010957b44: nvdimm_flush (STB_GLOBAL)
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
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a05d90)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
c000000000a05d90-c000000000a05df8: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c6a46)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffe0005c6a46-ffffffe0005c6a94: nvdimm_flush (STB_GLOBAL)
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
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170ad50)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8170ad50-ffffffff8170ad7e: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816de7d0)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pmem.c:nd_pmem_shutdown
  - drivers/nvdimm/pmem.c:nd_pmem_remove
  - drivers/nvdimm/pmem.c:pmem_make_request
  - drivers/nvdimm/pmem.c:pmem_make_request
```
**Symbols:**

```
ffffffff816de7d0-ffffffff816de7fe: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81749b20)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81749b20-ffffffff81749b4e: nvdimm_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region *nd_region, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81764fa0)
Location: drivers/nvdimm/region_devs.c:1082
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81764fa0-ffffffff81764fce: nvdimm_flush (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bio *bio</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
