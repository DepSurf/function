# Function: <code>bio_copy_from_iter</code>

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
In block/bio.c (ffffffff813b2406)
Location: block/bio.c:1015
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
In block/bio.c (ffffffff813f5a59)
Location: block/bio.c:1017
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
In block/bio.c (ffffffff8140f479)
Location: block/bio.c:1071
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
In block/bio.c (ffffffff8141cee9)
Location: block/bio.c:1087
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
In block/bio.c (ffffffff81447e06)
Location: block/bio.c:1092
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
In block/bio.c (ffffffff8147aeec)
Location: block/bio.c:1147
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
In block/bio.c (ffffffff81499172)
Location: block/bio.c:1071
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
In block/bio.c (ffffffff814c7367)
Location: block/bio.c:1129
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
In block/bio.c (ffffffff814e01ff)
Location: block/bio.c:1168
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
int bio_copy_from_iter(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8154a140)
Location: block/blk-map.c:45
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8154a140-ffffffff8154a20b: bio_copy_from_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_copy_from_iter(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81565ef0)
Location: block/blk-map.c:46
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81565ef0-ffffffff81565fbb: bio_copy_from_iter (STB_LOCAL)
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
In block/blk-map.c (ffffffff8156e696)
Location: block/blk-map.c:46
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
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
In block/blk-map.c (0)
Location: block/blk-map.c:46
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
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
In block/blk-map.c (ffffffff8167e9bc)
Location: block/blk-map.c:46
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
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
In block/blk-map.c (ffffffff8173b776)
Location: block/blk-map.c:46
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
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
In block/blk-map.c (ffffffff81777eb0)
Location: block/blk-map.c:48
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_copy_from_iter(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817b9e20)
Location: block/blk-map.c:48
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff817b9e20-ffffffff817b9f0e: bio_copy_from_iter (STB_LOCAL)
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
In block/bio.c (ffff8000105dcd50)
Location: block/bio.c:1168
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
In block/bio.c (c078a230)
Location: block/bio.c:1168
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
In block/bio.c (c00000000076e1c0)
Location: block/bio.c:1168
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
In block/bio.c (ffffffe00041ffd8)
Location: block/bio.c:1168
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
In block/bio.c (ffffffff814d87df)
Location: block/bio.c:1168
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
In block/bio.c (ffffffff814c918f)
Location: block/bio.c:1168
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
In block/bio.c (ffffffff814d486f)
Location: block/bio.c:1168
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
In block/bio.c (ffffffff814ed41f)
Location: block/bio.c:1168
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
</ul>
