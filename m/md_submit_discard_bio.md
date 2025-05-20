# Function: <code>md_submit_discard_bio</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_submit_discard_bio(struct mddev *mddev, struct md_rdev *rdev, struct bio *bio, sector_t start, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194ba90)
Location: drivers/md/md.c:8552
Inline: False
```
**Symbols:**

```
ffffffff8194ba90-ffffffff8194bb78: md_submit_discard_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void md_submit_discard_bio(struct mddev *mddev, struct md_rdev *rdev, struct bio *bio, sector_t start, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f0c90)
Location: drivers/md/md.c:8565
Inline: False
```
**Symbols:**

```
ffffffff819f0c90-ffffffff819f0d75: md_submit_discard_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void md_submit_discard_bio(struct mddev *mddev, struct md_rdev *rdev, struct bio *bio, sector_t start, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b5a0f0)
Location: drivers/md/md.c:8567
Inline: False
```
**Symbols:**

```
ffffffff81b5a0f0-ffffffff81b5a1fa: md_submit_discard_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void md_submit_discard_bio(struct mddev *mddev, struct md_rdev *rdev, struct bio *bio, sector_t start, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf2870)
Location: drivers/md/md.c:8578
Inline: False
```
**Symbols:**

```
ffffffff81cf2870-ffffffff81cf297a: md_submit_discard_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void md_submit_discard_bio(struct mddev *mddev, struct md_rdev *rdev, struct bio *bio, sector_t start, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d5a730)
Location: drivers/md/md.c:8587
Inline: False
```
**Symbols:**

```
ffffffff81d5a730-ffffffff81d5a83a: md_submit_discard_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void md_submit_discard_bio(struct mddev *mddev, struct md_rdev *rdev, struct bio *bio, sector_t start, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e11b60)
Location: drivers/md/md.c:8679
Inline: False
```
**Symbols:**

```
ffffffff81e11b60-ffffffff81e11c6a: md_submit_discard_bio (STB_GLOBAL)
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
