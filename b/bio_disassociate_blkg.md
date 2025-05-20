# Function: <code>bio_disassociate_blkg</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498603)
Location: block/bio.c:1983
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814980f0-ffffffff81498100: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c649c)
Location: block/bio.c:2017
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814c5f00-ffffffff814c5f46: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de3a5)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffffffff814de930-ffffffff814de976: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153e205)
Location: block/bio.c:1638
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
Direct callers:
  - block/bio.c:__bio_associate_blkg
```
**Symbols:**

```
ffffffff8153d940-ffffffff8153d989: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db580)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffff8000105db580-ffff8000105db618: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c078830c)
Location: block/bio.c:2059
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
**Symbols:**

```
c0788e44-c0788ed4: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b634)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
c00000000076c2e0-c00000000076c3b0: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e3ea)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffffffe00041e71c-ffffffe00041e78c: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6985)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffffffff814d6f10-ffffffff814d6f56: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7345)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffffffff814c78d0-ffffffff814c7916: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2a15)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffffffff814d2fa0-ffffffff814d2fe6: bio_disassociate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_disassociate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb535)
Location: block/bio.c:2059
Inline: True
```
**Symbols:**

```
ffffffff814ec090-ffffffff814ec0ed: bio_disassociate_blkg (STB_GLOBAL)
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
