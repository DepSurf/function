# Function: <code>badblocks_clear</code>

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
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81412cd0)
Location: block/badblocks.c:317
Inline: False
Direct callers:
  - drivers/md/md.c:rdev_clear_badblocks
  - drivers/md/md.c:rdev_clear_badblocks
```
**Symbols:**

```
ffffffff81412cd0-ffffffff81412f76: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8142e1a0)
Location: block/badblocks.c:339
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8142e1a0-ffffffff8142e4a1: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8143b4b0)
Location: block/badblocks.c:339
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8143b4b0-ffffffff8143b7ad: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814674c0)
Location: block/badblocks.c:339
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814674c0-ffffffff814677bd: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8149b330)
Location: block/badblocks.c:339
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8149b330-ffffffff8149b62c: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814b5640)
Location: block/badblocks.c:339
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814b5640-ffffffff814b593c: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e3b80)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814e3b80-ffffffff814e3e7a: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814fcf40)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814fcf40-ffffffff814fd23a: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8155ca70)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8155ca70-ffffffff8155cd5f: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81578bc0)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81578bc0-ffffffff81578eaf: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81580900)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81580900-ffffffff81580bed: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81cd8afa-ffffffff81cd8b64: badblocks_clear.cold (STB_LOCAL)
ffffffff815e5c00-ffffffff815e5f00: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:330
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81e8c567-ffffffff81e8c5fb: badblocks_clear.cold (STB_LOCAL)
ffffffff81694d70-ffffffff8169506c: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:330
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff82076a41-ffffffff82076ad5: badblocks_clear.cold (STB_LOCAL)
ffffffff81753db0-ffffffff817540ac: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:330
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff820f688a-ffffffff820f68f0: badblocks_clear.cold (STB_LOCAL)
ffffffff8178ff60-ffffffff81790259: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff817d3200)
Location: block/badblocks.c:1450
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff817d3200-ffffffff817d321a: badblocks_clear (STB_GLOBAL)
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
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffff8000105fee20)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffff8000105fee20-ffff8000105ff13c: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c07a9b84)
Location: block/badblocks.c:331
Inline: False
```
**Symbols:**

```
c07a9b84-c07a9ff8: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c000000000798850)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
c000000000798850-c000000000798c38: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffe00043a16a)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffe00043a16a-ffffffe00043a408: badblocks_clear (STB_GLOBAL)
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
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f5520)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814f5520-ffffffff814f581a: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e5a30)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
**Symbols:**

```
ffffffff814e5a30-ffffffff814e5d24: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f15b0)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff814f15b0-ffffffff814f18aa: badblocks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int badblocks_clear(struct badblocks *bb, sector_t s, int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8150a610)
Location: block/badblocks.c:331
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8150a610-ffffffff8150a902: badblocks_clear (STB_GLOBAL)
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
