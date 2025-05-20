# Function: <code>bio_devname</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814996d0)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814996d0-ffffffff814996eb: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814b3930)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814b3930-ffffffff814b394b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e1ec0)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814e1ec0-ffffffff814e1edb: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814fb280)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814fb280-ffffffff814fb29b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d460)
Location: block/bio.c:731
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
  - block/blk-core.c:blkcg_bio_issue_check
```
**Symbols:**

```
ffffffff8153d460-ffffffff8153d47b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a050)
Location: block/bio.c:731
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff8155a050-ffffffff8155a06b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562970)
Location: block/bio.c:687
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff81562970-ffffffff81562984: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6690)
Location: block/bio.c:770
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff815c6690-ffffffff815c66a4: bio_devname (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fd258)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffff8000105fd258-ffff8000105fd290: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a8174)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
c07a8174-c07a819c: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c000000000796a30)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
c000000000796a30-c000000000796a50: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe000438e9c)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffe000438e9c-ffffffe000438ed2: bio_devname (STB_GLOBAL)
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
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814f3860)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814f3860-ffffffff814f387b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e3d70)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814e3d70-ffffffff814e3d8b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814ef8f0)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff814ef8f0-ffffffff814ef90b: bio_devname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *bio_devname(struct bio *bio, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81508980)
Location: block/partition-generic.c:54
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
```
**Symbols:**

```
ffffffff81508980-ffffffff8150899b: bio_devname (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
