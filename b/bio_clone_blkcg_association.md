# Function: <code>bio_clone_blkcg_association</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkcg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6700)
Location: block/bio.c:2017
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
```
**Symbols:**

```
ffffffff813f6700-ffffffff813f6752: bio_clone_blkcg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkcg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814100e0)
Location: block/bio.c:2064
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
```
**Symbols:**

```
ffffffff814100e0-ffffffff81410132: bio_clone_blkcg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkcg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141db30)
Location: block/bio.c:2083
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
```
**Symbols:**

```
ffffffff8141db30-ffffffff8141db6e: bio_clone_blkcg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkcg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814465d0)
Location: block/bio.c:2013
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff814465d0-ffffffff81446610: bio_clone_blkcg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkcg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479a90)
Location: block/bio.c:2088
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff81479a90-ffffffff81479ad5: bio_clone_blkcg_association (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
</ul>
