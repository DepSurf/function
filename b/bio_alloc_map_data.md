# Function: <code>bio_alloc_map_data</code>

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
In block/bio.c (ffffffff813b21e0)
Location: block/bio.c:997
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff813f582c)
Location: block/bio.c:999
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff8140f24c)
Location: block/bio.c:1053
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff8141ccb9)
Location: block/bio.c:1069
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff81447c00)
Location: block/bio.c:1067
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff8147ad00)
Location: block/bio.c:1122
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff81498f80)
Location: block/bio.c:1046
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814c7157)
Location: block/bio.c:1105
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814dffd6)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81549990)
Location: block/blk-map.c:20
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81549990-ffffffff81549a17: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81565a20)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81565a20-ffffffff81565aa7: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156e050)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8156e050-ffffffff8156e0d7: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d2510)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff815d2510-ffffffff815d2597: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167e230)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8167e230-ffffffff8167e2bd: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173b400)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8173b400-ffffffff8173b48d: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81777b10)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81777b10-ffffffff81777bcb: bio_alloc_map_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio_map_data *bio_alloc_map_data(struct iov_iter *data, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817b9d30)
Location: block/blk-map.c:21
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff817b9d30-ffffffff817b9e05: bio_alloc_map_data (STB_LOCAL)
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
In block/bio.c (ffff8000105dcbb4)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (c078a03c)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (c00000000076deec)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffe00041fe7e)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814d85b6)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814c8f66)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814d4646)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814ed1f6)
Location: block/bio.c:1144
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
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
