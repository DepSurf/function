# Function: <code>bio_truncate</code>

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
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814df970)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffffffff814df970-ffffffff814dfb6e: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff8153f489)
Location: block/bio.c:555
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff8153e890-ffffffff8153ea5e: bio_truncate.part.0 (STB_LOCAL)
ffffffff8153f410-ffffffff8153f426: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff8155bc98)
Location: block/bio.c:557
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff8155aa00-ffffffff8155abbc: bio_truncate.part.0 (STB_LOCAL)
ffffffff8155bc10-ffffffff8155bc26: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff815642f4)
Location: block/bio.c:521
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff81563010-ffffffff815631c0: bio_truncate.part.0 (STB_LOCAL)
ffffffff815642a0-ffffffff815642b6: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff815c8784)
Location: block/bio.c:549
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff815c6ba0-ffffffff815c6da1: bio_truncate.part.0 (STB_LOCAL)
ffffffff81cd7f13-ffffffff81cd7f8d: bio_truncate.part.0.cold (STB_LOCAL)
ffffffff815c8730-ffffffff815c8746: bio_truncate (STB_GLOBAL)
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
In block/bio.c (ffffffff8167351e)
Location: block/bio.c:605
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
In block/bio.c (ffffffff8172f0be)
Location: block/bio.c:630
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
In block/bio.c (ffffffff8176b30e)
Location: block/bio.c:629
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad79e)
Location: block/bio.c:629
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dc4e0)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffff8000105dc4e0-ffff8000105dc6dc: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0789940)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
c0789940-c0789b18: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076d530)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
c00000000076d530-c00000000076d814: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f8b8)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffffffe00041f8b8-ffffffe00041faac: bio_truncate (STB_GLOBAL)
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
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d7f50)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffffffff814d7f50-ffffffff814d814e: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8900)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffffffff814c8900-ffffffff814c8afe: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d3fe0)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffffffff814d3fe0-ffffffff814d41de: bio_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_truncate(struct bio *bio, unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ecb70)
Location: block/bio.c:551
Inline: False
Direct callers:
  - fs/buffer.c:guard_bio_eod
```
**Symbols:**

```
ffffffff814ecb70-ffffffff814ecd90: bio_truncate (STB_GLOBAL)
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
