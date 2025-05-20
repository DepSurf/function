# Function: <code>handle_bad_sector</code>

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
In block/blk-core.c (ffffffff813b6304)
Location: block/blk-core.c:1838
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff813fb142)
Location: block/blk-core.c:1803
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff81414939)
Location: block/blk-core.c:1777
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff8142462c)
Location: block/blk-core.c:1923
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144cb40)
Location: block/blk-core.c:2021
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff8144cb40-ffffffff8144cbcf: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81485604)
Location: block/blk-core.c:2118
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81485604-ffffffff81485690: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149feb4)
Location: block/blk-core.c:746
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff8149feb4-ffffffff8149ff40: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cdf04)
Location: block/blk-core.c:733
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814cdf04-ffffffff814cdf8e: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e7224)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814e7224-ffffffff814e72ae: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8154619a)
Location: block/blk-core.c:797
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff8154619a-ffffffff81546224: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f3e0)
Location: block/blk-core.c:650
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff8155f3e0-ffffffff8155f47c: handle_bad_sector (STB_LOCAL)
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
In block/blk-core.c (ffffffff8156867f)
Location: block/blk-core.c:651
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
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
In block/blk-core.c (ffffffff815ccc56)
Location: block/blk-core.c:649
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
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
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4e08)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffff8000105e4e08-ffff8000105e4e9c: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791e44)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
c0791e44-c0791eec: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000778c4c)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
c000000000778c4c-c000000000778cfc: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000426280)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffe000426280-ffffffe0004262e4: handle_bad_sector (STB_LOCAL)
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
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df804)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814df804-ffffffff814df88e: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d01a4)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814d01a4-ffffffff814d022e: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db894)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814db894-ffffffff814db91e: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void handle_bad_sector(struct bio *bio, sector_t maxsector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f4704)
Location: block/blk-core.c:741
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814f4704-ffffffff814f478e: handle_bad_sector (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>sector_t maxsector</code>
</li>
</ul>
</details>
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
