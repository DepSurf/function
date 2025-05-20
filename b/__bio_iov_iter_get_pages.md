# Function: <code>__bio_iov_iter_get_pages</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814790d1)
Location: block/bio.c:915
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff81498cf7)
Location: block/bio.c:843
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff814c6d68)
Location: block/bio.c:881
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff814dfbd8)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153dcc0)
Location: block/bio.c:993
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
```
**Symbols:**

```
ffffffff8153dcc0-ffffffff8153de78: __bio_iov_iter_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a840)
Location: block/bio.c:993
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
```
**Symbols:**

```
ffffffff8155a840-ffffffff8155a9f5: __bio_iov_iter_get_pages (STB_LOCAL)
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
In block/bio.c (ffffffff815645e1)
Location: block/bio.c:994
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1085
Inline: False
```
**Symbols:**

```
ffffffff815c7500-ffffffff815c773c: __bio_iov_iter_get_pages (STB_LOCAL)
ffffffff81cd7f8d-ffffffff81cd7fa8: __bio_iov_iter_get_pages.cold (STB_LOCAL)
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
In block/bio.c (ffffffff81673a5f)
Location: block/bio.c:1205
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1247
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
```
**Symbols:**

```
ffffffff8172f4e0-ffffffff8172f86f: __bio_iov_iter_get_pages (STB_LOCAL)
ffffffff82075c15-ffffffff82075c4b: __bio_iov_iter_get_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1227
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
```
**Symbols:**

```
ffffffff8176b780-ffffffff8176baa5: __bio_iov_iter_get_pages (STB_LOCAL)
ffffffff820f5a66-ffffffff820f5aa0: __bio_iov_iter_get_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1237
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
```
**Symbols:**

```
ffffffff817adc40-ffffffff817adf46: __bio_iov_iter_get_pages (STB_LOCAL)
ffffffff821d2dab-ffffffff821d2de1: __bio_iov_iter_get_pages.cold (STB_LOCAL)
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
In block/bio.c (ffff8000105dc774)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (c0789b90)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (c00000000076d8dc)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffe00041fb22)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff814d81b8)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff814c8b68)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff814d4248)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
In block/bio.c (ffffffff814ecdf8)
Location: block/bio.c:920
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
