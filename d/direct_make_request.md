# Function: <code>direct_make_request</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814504e0)
Location: block/blk-core.c:2361
Inline: False
```
**Symbols:**

```
ffffffff814504e0-ffffffff814505aa: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814837c0)
Location: block/blk-core.c:2504
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814837c0-ffffffff81483897: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149ef80)
Location: block/blk-core.c:1134
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff8149ef80-ffffffff8149f051: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd070)
Location: block/blk-core.c:1096
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814cd070-ffffffff814cd13e: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e6300)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814e6300-ffffffff814e63ce: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81544f00)
Location: block/blk-core.c:1191
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81544f00-ffffffff81545028: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e38f8)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffff8000105e38f8-ffff8000105e3a14: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0790c00)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
c0790c00-c0790cf8: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777380)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
c000000000777380-c00000000077750c: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425382)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffe000425382-ffffffe00042546c: direct_make_request (STB_GLOBAL)
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
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814de8e0)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814de8e0-ffffffff814de9ae: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf280)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814cf280-ffffffff814cf34e: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da970)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814da970-ffffffff814daa3e: direct_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_qc_t direct_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3670)
Location: block/blk-core.c:1111
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814f3670-ffffffff814f3755: direct_make_request (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
