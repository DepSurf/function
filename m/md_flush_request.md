# Function: <code>md_flush_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81695070)
Location: drivers/md/md.c:430
Inline: False
```
**Symbols:**

```
ffffffff81695070-ffffffff81695199: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f5910)
Location: drivers/md/md.c:425
Inline: False
```
**Symbols:**

```
ffffffff816f5910-ffffffff816f5a43: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817270f0)
Location: drivers/md/md.c:438
Inline: False
```
**Symbols:**

```
ffffffff817270f0-ffffffff81727217: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173f900)
Location: drivers/md/md.c:454
Inline: False
```
**Symbols:**

```
ffffffff8173f900-ffffffff8173fa1d: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b1920)
Location: drivers/md/md.c:489
Inline: False
```
**Symbols:**

```
ffffffff817b1920-ffffffff817b1a3d: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f57d0)
Location: drivers/md/md.c:471
Inline: False
```
**Symbols:**

```
ffffffff817f57d0-ffffffff817f599b: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818216b0)
Location: drivers/md/md.c:463
Inline: False
```
**Symbols:**

```
ffffffff818216b0-ffffffff8182189e: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:548
Inline: False
```
**Symbols:**

```
ffffffff8186e7e0-ffffffff8186e7f3: md_flush_request.cold (STB_LOCAL)
ffffffff818637f0-ffffffff818639a5: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81895540)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffffffff81895540-ffffffff818956e8: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81965b60)
Location: drivers/md/md.c:685
Inline: False
```
**Symbols:**

```
ffffffff81965b60-ffffffff81965d08: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196c630)
Location: drivers/md/md.c:663
Inline: False
```
**Symbols:**

```
ffffffff8196c630-ffffffff8196c7cf: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819515f0)
Location: drivers/md/md.c:606
Inline: False
```
**Symbols:**

```
ffffffff819515f0-ffffffff8195178f: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f6b30)
Location: drivers/md/md.c:607
Inline: False
```
**Symbols:**

```
ffffffff819f6b30-ffffffff819f6ccf: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b556b0)
Location: drivers/md/md.c:612
Inline: False
```
**Symbols:**

```
ffffffff81b556b0-ffffffff81b55872: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cee770)
Location: drivers/md/md.c:605
Inline: False
```
**Symbols:**

```
ffffffff81cee770-ffffffff81cee932: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d574f0)
Location: drivers/md/md.c:573
Inline: False
```
**Symbols:**

```
ffffffff81d574f0-ffffffff81d576b2: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e14130)
Location: drivers/md/md.c:622
Inline: False
```
**Symbols:**

```
ffffffff81e14130-ffffffff81e14340: md_flush_request (STB_GLOBAL)
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
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aeada8)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffff800010aeada8-ffff800010aeafc0: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc3678)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
c0bc3678-c0bc3870: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd6260)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
c000000000bd6260-c000000000bd6504: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e0258)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffffffe0006e0258-ffffffe0006e0476: md_flush_request (STB_GLOBAL)
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
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183b3c0)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffffffff8183b3c0-ffffffff8183b568: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81802a30)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffffffff81802a30-ffffffff81802bc8: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188a9f0)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffffffff8188a9f0-ffffffff8188ab98: md_flush_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool md_flush_request(struct mddev *mddev, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a1030)
Location: drivers/md/md.c:559
Inline: False
```
**Symbols:**

```
ffffffff818a1030-ffffffff818a11ce: md_flush_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
