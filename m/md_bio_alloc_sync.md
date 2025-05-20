# Function: <code>md_bio_alloc_sync</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173a780)
Location: drivers/md/md.c:206
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8173a780-ffffffff8173a7c3: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817acda0)
Location: drivers/md/md.c:206
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff817acda0-ffffffff817acde3: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f2ec0)
Location: drivers/md/md.c:226
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff817f2ec0-ffffffff817f2f08: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181eea0)
Location: drivers/md/md.c:217
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8181eea0-ffffffff8181eee8: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81861310)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81861310-ffffffff81861358: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81892f40)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81892f40-ffffffff81892f88: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81961639)
Location: drivers/md/md.c:357
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81967f69)
Location: drivers/md/md.c:353
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae45c0)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffff800010ae45c0-ffff800010ae4620: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc7bfc)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
c0bc7bfc-c0bc7c50: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd0420)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
c000000000bd0420-c000000000bd04a8: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006db7ca)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffe0006db7ca-ffffffe0006db828: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81838dc0)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81838dc0-ffffffff81838e08: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81800430)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81800430-ffffffff81800478: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818883f0)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff818883f0-ffffffff81888438: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bio *md_bio_alloc_sync(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a5990)
Location: drivers/md/md.c:263
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff818a5990-ffffffff818a59d8: md_bio_alloc_sync (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
