# Function: <code>badblocks_check</code>

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
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814126d0)
Location: block/badblocks.c:61
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814126d0-ffffffff81412844: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8142db30)
Location: block/badblocks.c:61
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8142db30-ffffffff8142dca4: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8143ae80)
Location: block/badblocks.c:61
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8143ae80-ffffffff8143afe7: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81466ea0)
Location: block/badblocks.c:61
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81466ea0-ffffffff81467007: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8149ad30)
Location: block/badblocks.c:61
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8149ad30-ffffffff8149ae8b: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814b5040)
Location: block/badblocks.c:61
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff814b5040-ffffffff814b519b: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e35e0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff814e35e0-ffffffff814e3708: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814fc9a0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff814fc9a0-ffffffff814fcac8: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8155c100)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff8155c100-ffffffff8155c232: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81578260)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff81578260-ffffffff8157838c: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8157ffe0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff8157ffe0-ffffffff8158010c: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff81cd8987-ffffffff81cd8a14: badblocks_check.cold (STB_LOCAL)
ffffffff815e52d0-ffffffff815e5410: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff81e8c401-ffffffff81e8c47b: badblocks_check.cold (STB_LOCAL)
ffffffff81694360-ffffffff816944c7: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff820768e5-ffffffff8207695f: badblocks_check.cold (STB_LOCAL)
ffffffff81753320-ffffffff81753487: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff820f677d-ffffffff820f67df: badblocks_check.cold (STB_LOCAL)
ffffffff8178f4e0-ffffffff8178f648: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff817d2e40)
Location: block/badblocks.c:1407
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
**Symbols:**

```
ffffffff817d2e40-ffffffff817d2e5f: badblocks_check (STB_GLOBAL)
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
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffff8000105fe400)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffff8000105fe400-ffff8000105fe550: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c07a9290)
Location: block/badblocks.c:53
Inline: False
```
**Symbols:**

```
c07a9290-c07a94dc: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c0000000007980f0)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
c0000000007980f0-c000000000798250: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffe000439c6a)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffe000439c6a-ffffffe000439d76: badblocks_check (STB_GLOBAL)
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
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f4f80)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff814f4f80-ffffffff814f50a8: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e5490)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pmem.c:__pmem_direct_access
  - drivers/nvdimm/pmem.c:pmem_do_bvec
  - drivers/nvdimm/btt.c:btt_write_pg
```
**Symbols:**

```
ffffffff814e5490-ffffffff814e55b8: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f1010)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff814f1010-ffffffff814f1138: badblocks_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int badblocks_check(struct badblocks *bb, sector_t s, int sectors, sector_t *first_bad, int *bad_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8150a070)
Location: block/badblocks.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff8150a070-ffffffff8150a198: badblocks_check (STB_GLOBAL)
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
