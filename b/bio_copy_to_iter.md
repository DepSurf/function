# Function: <code>bio_copy_to_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2080)
Location: block/bio.c:1046
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f56d4)
Location: block/bio.c:1048
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140f0f2)
Location: block/bio.c:1102
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141cb61)
Location: block/bio.c:1118
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81447b41)
Location: block/bio.c:1123
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147ac6e)
Location: block/bio.c:1178
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498eee)
Location: block/bio.c:1102
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7078)
Location: block/bio.c:1160
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dfee8)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bio_copy_to_iter(struct bio *bio, struct iov_iter iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8154a510)
Location: block/blk-map.c:76
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8154a510-ffffffff8154a5c9: bio_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_copy_to_iter(struct bio *bio, struct iov_iter iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815662f0)
Location: block/blk-map.c:77
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_unmap_user
```
**Symbols:**

```
ffffffff815662f0-ffffffff815663a9: bio_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156e9b0)
Location: block/blk-map.c:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d2fe0)
Location: block/blk-map.c:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167ec84)
Location: block/blk-map.c:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173bc38)
Location: block/blk-map.c:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81778378)
Location: block/blk-map.c:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817ba758)
Location: block/blk-map.c:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dca9c)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c0789f4c)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076dd74)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041fd96)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d84c8)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8e78)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d4558)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ed108)
Location: block/bio.c:1199
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
