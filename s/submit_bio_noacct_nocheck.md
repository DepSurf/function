# Function: <code>submit_bio_noacct_nocheck</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void submit_bio_noacct_nocheck(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679240)
Location: block/blk-core.c:731
Inline: True
Direct callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
```
**Symbols:**

```
ffffffff81679240-ffffffff81679355: submit_bio_noacct_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void submit_bio_noacct_nocheck(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817355f0)
Location: block/blk-core.c:685
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
```
**Symbols:**

```
ffffffff817355f0-ffffffff817357c4: submit_bio_noacct_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void submit_bio_noacct_nocheck(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:683
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
```
**Symbols:**

```
ffffffff820f5ace-ffffffff820f5ae3: submit_bio_noacct_nocheck.cold (STB_LOCAL)
ffffffff81771b90-ffffffff81771d74: submit_bio_noacct_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void submit_bio_noacct_nocheck(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:693
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
```
**Symbols:**

```
ffffffff821d2eb9-ffffffff821d2ece: submit_bio_noacct_nocheck.cold (STB_LOCAL)
ffffffff817b3ed0-ffffffff817b40b4: submit_bio_noacct_nocheck (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
