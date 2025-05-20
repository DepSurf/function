# Function: <code>blk_ksm_evict_key</code>

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
int blk_ksm_evict_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff81581650)
Location: block/keyslot-manager.c:315
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff81581650-ffffffff81581754: blk_ksm_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_ksm_evict_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8159e680)
Location: block/keyslot-manager.c:322
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff8159e680-ffffffff8159e784: blk_ksm_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_ksm_evict_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff815a5460)
Location: block/keyslot-manager.c:360
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff815a5460-ffffffff815a55c5: blk_ksm_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_ksm_evict_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8160df30)
Location: block/keyslot-manager.c:360
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key
```
**Symbols:**

```
ffffffff8160df30-ffffffff8160e095: blk_ksm_evict_key (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
