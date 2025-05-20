# Function: <code>ext4_finish_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8129f680)
Location: fs/ext4/page-io.c:61
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff8129f680-ffffffff8129f8ac: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812cdf70)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff812cdf70-ffffffff812ce16b: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812e3d60)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff812e3d60-ffffffff812e3f5b: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8131d960)
Location: fs/ext4/page-io.c:61
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff8131d960-ffffffff8131db8b: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81341f70)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff81341f70-ffffffff8134219b: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff8136fe10-ffffffff8137001c: ext4_finish_bio (STB_LOCAL)
ffffffff81370b30-ffffffff81370b5f: ext4_finish_bio.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff813882a0-ffffffff813884ad: ext4_finish_bio (STB_LOCAL)
ffffffff81388fc6-ffffffff81388ff5: ext4_finish_bio.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff813b2300-ffffffff813b256b: ext4_finish_bio (STB_LOCAL)
ffffffff813b30e3-ffffffff813b3104: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813cb350-ffffffff813cb5c0: ext4_finish_bio (STB_LOCAL)
ffffffff813cc18c-ffffffff813cc1ad: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff814174b0-ffffffff814176d3: ext4_finish_bio (STB_LOCAL)
ffffffff8141826e-ffffffff8141828f: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff8142afc0-ffffffff8142b1d4: ext4_finish_bio (STB_LOCAL)
ffffffff81bec511-ffffffff81bec532: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff81431b30-ffffffff81431d44: ext4_finish_bio (STB_LOCAL)
ffffffff81bde5c3-ffffffff81bde5e4: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff81485380-ffffffff81485597: ext4_finish_bio (STB_LOCAL)
ffffffff81cccde1-ffffffff81ccce02: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff81508770-ffffffff81508a05: ext4_finish_bio (STB_LOCAL)
ffffffff81e7fcb2-ffffffff81e7fcd3: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815a3270)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff815a3270-ffffffff815a3518: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff815d9b60-ffffffff815d9fa4: ext4_finish_bio (STB_LOCAL)
ffffffff820efcfd-ffffffff820efd52: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:100
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffff81612250-ffffffff81612684: ext4_finish_bio (STB_LOCAL)
ffffffff821ccdd3-ffffffff821cce7b: ext4_finish_bio.cold (STB_LOCAL)
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
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffff8000104a31a0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffff8000104a31a0-ffff8000104a34b8: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c06651d0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
c06651d0-c06654a8: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0000000005d00c0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
c0000000005d00c0-c0000000005d04c0: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffe000324ad0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
```
**Symbols:**

```
ffffffe000324ad0-ffffffe000324ce8: ext4_finish_bio (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813c3930-ffffffff813c3ba0: ext4_finish_bio (STB_LOCAL)
ffffffff813c476c-ffffffff813c478d: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813b43c0-ffffffff813b4620: ext4_finish_bio (STB_LOCAL)
ffffffff813b51ec-ffffffff813b520d: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813c0dc0-ffffffff813c1030: ext4_finish_bio (STB_LOCAL)
ffffffff813c1bfc-ffffffff813c1c1d: ext4_finish_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ext4_finish_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:62
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813d5ef0-ffffffff813d618e: ext4_finish_bio (STB_LOCAL)
ffffffff813d6d75-ffffffff813d6d96: ext4_finish_bio.cold (STB_LOCAL)
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
