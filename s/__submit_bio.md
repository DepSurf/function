# Function: <code>__submit_bio</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156157a)
Location: block/blk-core.c:927
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
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
In block/blk-core.c (ffffffff81569cd6)
Location: block/blk-core.c:913
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_qc_t __submit_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cd3f0)
Location: block/blk-core.c:909
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff815cd3f0-ffffffff815cd60c: __submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __submit_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678b00)
Location: block/blk-core.c:640
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff81678b00-ffffffff81678c9b: __submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __submit_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734f90)
Location: block/blk-core.c:594
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff81734f90-ffffffff8173512b: __submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __submit_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:592
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff817714f0-ffffffff817716af: __submit_bio (STB_LOCAL)
ffffffff820f5ab5-ffffffff820f5ace: __submit_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __submit_bio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:602
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff817b3830-ffffffff817b39ef: __submit_bio (STB_LOCAL)
ffffffff821d2ea0-ffffffff821d2eb9: __submit_bio.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_qc_t</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
