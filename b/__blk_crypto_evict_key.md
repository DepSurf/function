# Function: <code>__blk_crypto_evict_key</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __blk_crypto_evict_key(struct blk_crypto_profile *profile, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c2a50)
Location: block/blk-crypto-profile.c:373
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff816c2a50-ffffffff816c2bb9: __blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __blk_crypto_evict_key(struct blk_crypto_profile *profile, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783de0)
Location: block/blk-crypto-profile.c:374
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff81783de0-ffffffff81783f49: __blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __blk_crypto_evict_key(struct blk_crypto_profile *profile, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c40c0)
Location: block/blk-crypto-profile.c:363
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff817c40c0-ffffffff817c4231: __blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __blk_crypto_evict_key(struct blk_crypto_profile *profile, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81808d50)
Location: block/blk-crypto-profile.c:363
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff81808d50-ffffffff81808ec1: __blk_crypto_evict_key (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
