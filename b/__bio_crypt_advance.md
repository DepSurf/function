# Function: <code>__bio_crypt_advance</code>

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
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815819c0)
Location: block/blk-crypto.c:124
Inline: False
Direct callers:
  - block/bio.c:bio_advance
```
**Symbols:**

```
ffffffff815819c0-ffffffff81581a02: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159e9b0)
Location: block/blk-crypto.c:135
Inline: False
Direct callers:
  - block/bio.c:bio_advance
```
**Symbols:**

```
ffffffff8159e9b0-ffffffff8159e9f2: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5780)
Location: block/blk-crypto.c:135
Inline: False
Direct callers:
  - block/bio.c:bio_advance
```
**Symbols:**

```
ffffffff815a5780-ffffffff815a57c2: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:135
Inline: False
Direct callers:
  - block/bio.c:bio_advance
```
**Symbols:**

```
ffffffff81cda662-ffffffff81cda688: __bio_crypt_advance.cold (STB_LOCAL)
ffffffff8160e250-ffffffff8160e2a8: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:137
Inline: False
Direct callers:
  - block/bio.c:__bio_advance
```
**Symbols:**

```
ffffffff81e8e196-ffffffff81e8e1bc: __bio_crypt_advance.cold (STB_LOCAL)
ffffffff816c1880-ffffffff816c18e6: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:143
Inline: False
Direct callers:
  - block/bio.c:__bio_advance
```
**Symbols:**

```
ffffffff820773c9-ffffffff820773ef: __bio_crypt_advance.cold (STB_LOCAL)
ffffffff81782a10-ffffffff81782a76: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:144
Inline: False
Direct callers:
  - block/bio.c:__bio_advance
```
**Symbols:**

```
ffffffff820f740e-ffffffff820f7434: __bio_crypt_advance.cold (STB_LOCAL)
ffffffff817c2b90-ffffffff817c2bf6: __bio_crypt_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __bio_crypt_advance(struct bio *bio, unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:144
Inline: False
Direct callers:
  - block/bio.c:__bio_advance
```
**Symbols:**

```
ffffffff821d4e36-ffffffff821d4e5c: __bio_crypt_advance.cold (STB_LOCAL)
ffffffff81807820-ffffffff81807886: __bio_crypt_advance (STB_GLOBAL)
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
