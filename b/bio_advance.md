# Function: <code>bio_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0870)
Location: block/bio.c:894
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813b0870-ffffffff813b0943: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f3f80)
Location: block/bio.c:896
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813f3f80-ffffffff813f4053: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140d920)
Location: block/bio.c:950
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8140d920-ffffffff8140da01: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141c440)
Location: block/bio.c:966
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_remap_zone_report
```
**Symbols:**

```
ffffffff8141c440-ffffffff8141c52c: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81447000)
Location: block/bio.c:964
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_remap_zone_report
```
**Symbols:**

```
ffffffff81447000-ffffffff814470ec: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479c10)
Location: block/bio.c:1022
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_remap_zone_report
```
**Symbols:**

```
ffffffff81479c10-ffffffff81479cfd: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497380)
Location: block/bio.c:946
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81497380-ffffffff8149745e: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c4cd0)
Location: block/bio.c:1005
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814c4cd0-ffffffff814c4dae: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ddb70)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814ddb70-ffffffff814ddc4e: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153da80)
Location: block/bio.c:1177
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff8153da80-ffffffff8153db5a: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a600)
Location: block/bio.c:1180
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff8155a600-ffffffff8155a6da: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562dd0)
Location: block/bio.c:1181
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81562dd0-ffffffff81562eaa: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1275
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81cd7eff-ffffffff81cd7f13: bio_advance.cold (STB_LOCAL)
ffffffff815c6a40-ffffffff815c6b26: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671a92)
Location: include/linux/bio.h:134
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
```
```
In block/blk-mq.c (ffffffff81686e29)
Location: include/linux/bio.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d332)
Location: include/linux/bio.h:134
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
```
```
In block/blk-mq.c (ffffffff81744b09)
Location: include/linux/bio.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817696e2)
Location: include/linux/bio.h:136
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
```
```
In block/blk-mq.c (ffffffff81780979)
Location: include/linux/bio.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab762)
Location: include/linux/bio.h:136
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
```
```
In block/blk-mq.c (ffffffff817c2f39)
Location: include/linux/bio.h:136
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
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
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da048)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffff8000105da048-ffff8000105da178: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787820)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c0787820-c0787960: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a790)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c00000000076a790-c00000000076a950: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041db86)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffe00041db86-ffffffe00041dc84: bio_advance (STB_GLOBAL)
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
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6150)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814d6150-ffffffff814d622e: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6b70)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814c6b70-ffffffff814c6c4e: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d21e0)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814d21e0-ffffffff814d22be: bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eac90)
Location: block/bio.c:1044
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - block/blk-core.c:blk_update_request
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814eac90-ffffffff814ead6e: bio_advance (STB_GLOBAL)
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
