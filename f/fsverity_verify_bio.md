# Function: <code>fsverity_verify_bio</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81351740)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff81351740-ffffffff81351902: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813981f0)
Location: fs/verity/verify.c:223
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813981f0-ffffffff813983e5: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813a9a70)
Location: fs/verity/verify.c:223
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813a9a70-ffffffff813a9c65: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813b0fb0)
Location: fs/verity/verify.c:223
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813b0fb0-ffffffff813b119b: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:223
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff81cc72d3-ffffffff81cc7308: fsverity_verify_bio.cold (STB_LOCAL)
ffffffff81400c90-ffffffff81400e84: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:223
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff81e7983a-ffffffff81e79873: fsverity_verify_bio.cold (STB_LOCAL)
ffffffff81474d10-ffffffff81474fc5: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:212
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff8206aaff-ffffffff8206ab21: fsverity_verify_bio.cold (STB_LOCAL)
ffffffff815070f0-ffffffff815072fd: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:308
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff820eaa2a-ffffffff820eaa90: fsverity_verify_bio.cold (STB_LOCAL)
ffffffff8153e5e0-ffffffff8153e8c6: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:308
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff821c76fb-ffffffff821c773a: fsverity_verify_bio.cold (STB_LOCAL)
ffffffff81573b80-ffffffff81573da2: fsverity_verify_bio (STB_GLOBAL)
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
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffff800010413870)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffff800010413870-ffff800010413a84: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c05dfb20)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
c05dfb20-c05dfd44: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c000000000521820)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
c000000000521820-c000000000521ae0: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffe0002bb264)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffe0002bb264-ffffffe0002bb404: fsverity_verify_bio (STB_GLOBAL)
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
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81349d20)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff81349d20-ffffffff81349ee2: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8133aa00)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff8133aa00-ffffffff8133abc2: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813477f0)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813477f0-ffffffff813479b2: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsverity_verify_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8135aaf0)
Location: fs/verity/verify.c:221
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff8135aaf0-ffffffff8135acb2: fsverity_verify_bio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
