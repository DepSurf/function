# Function: <code>__bio_advance</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1332
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-mq.c:blk_update_request
```
**Symbols:**

```
ffffffff81e8b33e-ffffffff81e8b352: __bio_advance.cold (STB_LOCAL)
ffffffff81671940-ffffffff81671a3d: __bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1395
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-mq.c:blk_update_request
```
**Symbols:**

```
ffffffff82075bb8-ffffffff82075bcc: __bio_advance.cold (STB_LOCAL)
ffffffff8172d1d0-ffffffff8172d2cd: __bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1380
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-mq.c:blk_update_request
```
**Symbols:**

```
ffffffff820f59fb-ffffffff820f5a17: __bio_advance.cold (STB_LOCAL)
ffffffff81769570-ffffffff81769673: __bio_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __bio_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1392
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/blk-mq.c:blk_update_request
```
**Symbols:**

```
ffffffff821d2ccf-ffffffff821d2ceb: __bio_advance.cold (STB_LOCAL)
ffffffff817ab5f0-ffffffff817ab6f3: __bio_advance (STB_GLOBAL)
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
