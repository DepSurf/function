# Function: <code>blk_crypto_split_bio_if_needed</code>

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
bool blk_crypto_split_bio_if_needed(struct bio **bio_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff81582210)
Location: block/blk-crypto-fallback.c:209
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81582210-ffffffff81582369: blk_crypto_split_bio_if_needed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_crypto_split_bio_if_needed(struct bio **bio_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8159f1e0)
Location: block/blk-crypto-fallback.c:209
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8159f1e0-ffffffff8159f31a: blk_crypto_split_bio_if_needed (STB_LOCAL)
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
In block/blk-crypto-fallback.c (ffffffff815a65eb)
Location: block/blk-crypto-fallback.c:212
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In block/blk-crypto-fallback.c (ffffffff8160f0fb)
Location: block/blk-crypto-fallback.c:212
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
</ul>
