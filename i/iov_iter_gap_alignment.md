# Function: <code>iov_iter_gap_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814430d0)
Location: lib/iov_iter.c:521
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814430d0-ffffffff814432c2: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814603e0)
Location: lib/iov_iter.c:864
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814603e0-ffffffff81460615: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814657b0)
Location: lib/iov_iter.c:991
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814657b0-ffffffff8146597d: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491610)
Location: lib/iov_iter.c:993
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81491610-ffffffff814917f5: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c65e0)
Location: lib/iov_iter.c:1123
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814c65e0-ffffffff814c67d0: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dad50)
Location: lib/iov_iter.c:1195
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814dad50-ffffffff814daf5a: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8150ad3b-ffffffff8150ad54: iov_iter_gap_alignment.cold (STB_LOCAL)
ffffffff81506400-ffffffff81506641: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815246f0)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff815246f0-ffffffff8152492c: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81588f30)
Location: lib/iov_iter.c:1245
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81588f30-ffffffff81589133: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5620)
Location: lib/iov_iter.c:1252
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff815a5620-ffffffff815a57c9: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ac0b0)
Location: lib/iov_iter.c:1382
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff815ac0b0-ffffffff815ac4a9: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816142c0)
Location: lib/iov_iter.c:1293
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff816142c0-ffffffff8161432c: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0c20)
Location: lib/iov_iter.c:1345
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff816e0c20-ffffffff816e0cb9: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d1130)
Location: lib/iov_iter.c:1268
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff817d1130-ffffffff817d11b3: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8180feb0)
Location: lib/iov_iter.c:947
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8180feb0-ffffffff8180ff33: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855b30)
Location: lib/iov_iter.c:844
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81855b30-ffffffff81855bb3: iov_iter_gap_alignment (STB_GLOBAL)
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
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062ed90)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffff80001062ed90-ffff80001062efb8: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d56a0)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
c07d56a0-c07d5914: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d2610)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
c0000000007d2610-c0000000007d294c: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045e118)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffe00045e118-ffffffe00045e2ee: iov_iter_gap_alignment (STB_GLOBAL)
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
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151ccd0)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8151ccd0-ffffffff8151cf0c: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150cfc0)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8150cfc0-ffffffff8150d1fc: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518d60)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81518d60-ffffffff81518f9c: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int iov_iter_gap_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532550)
Location: lib/iov_iter.c:1209
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81532550-ffffffff8153278c: iov_iter_gap_alignment (STB_GLOBAL)
```
</details>
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
