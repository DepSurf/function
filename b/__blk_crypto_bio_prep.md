# Function: <code>__blk_crypto_bio_prep</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581b70)
Location: block/blk-crypto.c:252
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff81581b70-ffffffff81581c03: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159eb60)
Location: block/blk-crypto.c:263
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff8159eb60-ffffffff8159ebe9: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5930)
Location: block/blk-crypto.c:263
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio_noacct
```
**Symbols:**

```
ffffffff815a5930-ffffffff815a5a4c: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e400)
Location: block/blk-crypto.c:263
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
```
**Symbols:**

```
ffffffff8160e400-ffffffff8160e51c: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1aa0)
Location: block/blk-crypto.c:266
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
```
**Symbols:**

```
ffffffff816c1aa0-ffffffff816c1bc4: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782c90)
Location: block/blk-crypto.c:272
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
```
**Symbols:**

```
ffffffff81782c90-ffffffff81782db4: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2ec0)
Location: block/blk-crypto.c:273
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
```
**Symbols:**

```
ffffffff817c2ec0-ffffffff817c302f: __blk_crypto_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __blk_crypto_bio_prep(struct bio **bio_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807b50)
Location: block/blk-crypto.c:273
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
```
**Symbols:**

```
ffffffff81807b50-ffffffff81807cbf: __blk_crypto_bio_prep (STB_GLOBAL)
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
