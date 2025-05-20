# Function: <code>xen_biovec_phys_mergeable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff814d27b0)
Location: drivers/xen/biomerge.c:6
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:attempt_merge
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff814d27b0-ffffffff814d29bd: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff815234e0)
Location: drivers/xen/biomerge.c:6
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff815234e0-ffffffff815236ec: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff8154f9c0)
Location: drivers/xen/biomerge.c:6
Inline: False
Direct callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff8154f9c0-ffffffff8154fba7: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff815640f0)
Location: drivers/xen/biomerge.c:6
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff815640f0-ffffffff81564265: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff815c8240)
Location: drivers/xen/biomerge.c:7
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff815c8240-ffffffff815c83b5: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81600ab0)
Location: drivers/xen/biomerge.c:7
Inline: False
Direct callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81600ab0-ffffffff81600c1f: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct bio_vec *vec2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff8161bb80)
Location: drivers/xen/biomerge.c:7
Inline: False
Direct callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff8161bb80-ffffffff8161bcef: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff8164f800)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_add_pc_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff8164f800-ffffffff8164f96d: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81671db0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81671db0-ffffffff81671f1d: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81722480)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81722480-ffffffff817225e3: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff8173f0e0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff8173f0e0-ffffffff8173f255: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81722b30)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81722b30-ffffffff81722ca9: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff817a1980)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff817a1980-ffffffff817a1af9: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff818db9b0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff818db9b0-ffffffff818dbb23: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81a2eaf0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81a2eaf0-ffffffff81a2ec63: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81a782b0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:bvec_try_merge_page
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81a782b0-ffffffff81a78423: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81aca5d0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:bvec_try_merge_page
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81aca5d0-ffffffff81aca743: xen_biovec_phys_mergeable (STB_GLOBAL)
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
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffff80001083c980)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffff80001083c980-ffff80001083ca30: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81637e70)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81637e70-ffffffff81637fdd: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff81665bf0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff81665bf0-ffffffff81665d5d: xen_biovec_phys_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec *vec1, const struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/biomerge.c (ffffffff816801a0)
Location: drivers/xen/biomerge.c:8
Inline: False
Direct callers:
  - block/bio.c:__bio_try_merge_page
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
**Symbols:**

```
ffffffff816801a0-ffffffff8168030d: xen_biovec_phys_mergeable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct bio_vec *vec2</code>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
