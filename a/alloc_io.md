# Function: <code>alloc_io</code>

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
In drivers/md/dm.c (ffffffff816a27e8)
Location: drivers/md/dm.c:630
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff817030e8)
Location: drivers/md/dm.c:484
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff81734fb8)
Location: drivers/md/dm.c:484
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff8174e3d6)
Location: drivers/md/dm.c:482
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff817c03f6)
Location: drivers/md/dm.c:489
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807430)
Location: drivers/md/dm.c:534
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81807430-ffffffff81807551: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833460)
Location: drivers/md/dm.c:585
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81833460-ffffffff81833555: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875390)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81875390-ffffffff8187548f: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7140)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff818a7140-ffffffff818a723f: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81976ed0)
Location: drivers/md/dm.c:596
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81976ed0-ffffffff81976fb4: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197bb00)
Location: drivers/md/dm.c:631
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8197bb00-ffffffff8197bbe4: alloc_io (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff81961309)
Location: drivers/md/dm.c:636
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff81a0af3b)
Location: drivers/md/dm.c:516
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff81b728ec)
Location: drivers/md/dm.c:574
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In drivers/md/dm.c (ffffffff81d0f6c9)
Location: drivers/md/dm.c:569
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In drivers/md/dm.c (ffffffff81d78ac9)
Location: drivers/md/dm.c:573
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:573
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
```
**Symbols:**

```
ffffffff81e2cef0-ffffffff81e2d003: alloc_io (STB_LOCAL)
ffffffff8220b340-ffffffff8220b355: alloc_io.cold (STB_LOCAL)
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
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afc368)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffff800010afc368-ffff800010afc460: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdcb64)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c0bdcb64-c0bdcc50: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beaaa0)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c000000000beaaa0-c000000000beabec: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ed6d0)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffe0006ed6d0-ffffffe0006ed7aa: alloc_io (STB_LOCAL)
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
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184cfc0)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8184cfc0-ffffffff8184d0bf: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818145e0)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff818145e0-ffffffff818146df: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189c5f0)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8189c5f0-ffffffff8189c6ef: alloc_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dm_io *alloc_io(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b8830)
Location: drivers/md/dm.c:565
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff818b8830-ffffffff818b892f: alloc_io (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
