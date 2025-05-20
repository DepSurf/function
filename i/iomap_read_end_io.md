# Function: <code>iomap_read_end_io</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813234f0)
Location: fs/iomap.c:272
Inline: False
```
**Symbols:**

```
ffffffff813234f0-ffffffff813235a6: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b590)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffff8134b590-ffffffff8134b695: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363850)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffff81363850-ffffffff81363964: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aace0)
Location: fs/iomap/buffered-io.c:198
Inline: False
```
**Symbols:**

```
ffffffff813aace0-ffffffff813aade9: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bc5b0)
Location: fs/iomap/buffered-io.c:190
Inline: False
```
**Symbols:**

```
ffffffff813bc5b0-ffffffff813bc6a6: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3280)
Location: fs/iomap/buffered-io.c:190
Inline: False
```
**Symbols:**

```
ffffffff813c3280-ffffffff813c339c: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81412c00)
Location: fs/iomap/buffered-io.c:190
Inline: False
```
**Symbols:**

```
ffffffff81412c00-ffffffff81412d1c: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:182
Inline: False
```
**Symbols:**

```
ffffffff81489cb0-ffffffff8148a197: iomap_read_end_io (STB_LOCAL)
ffffffff81e7a104-ffffffff81e7a181: iomap_read_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:187
Inline: False
```
**Symbols:**

```
ffffffff8151d300-ffffffff8151d630: iomap_read_end_io (STB_LOCAL)
ffffffff8206afa9-ffffffff8206b00f: iomap_read_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:187
Inline: False
```
**Symbols:**

```
ffffffff815555b0-ffffffff815558cf: iomap_read_end_io (STB_LOCAL)
ffffffff820eaf13-ffffffff820eaf79: iomap_read_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:277
Inline: False
```
**Symbols:**

```
ffffffff8158b800-ffffffff8158bb4d: iomap_read_end_io (STB_LOCAL)
ffffffff821c7f1e-ffffffff821c7f80: iomap_read_end_io.cold (STB_LOCAL)
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
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042af98)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffff80001042af98-ffff80001042b134: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f2d40)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
c05f2d40-c05f2e78: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a910)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
c00000000053a910-c00000000053ab34: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7d96)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffe0002c7d96-ffffffe0002c7eca: iomap_read_end_io (STB_LOCAL)
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
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135be30)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffff8135be30-ffffffff8135bf44: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134cad0)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffff8134cad0-ffffffff8134cbe4: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359900)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffff81359900-ffffffff81359a14: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iomap_read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136cff0)
Location: fs/iomap/buffered-io.c:167
Inline: False
```
**Symbols:**

```
ffffffff8136cff0-ffffffff8136d104: iomap_read_end_io (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
