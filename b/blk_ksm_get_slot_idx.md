# Function: <code>blk_ksm_get_slot_idx</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_ksm_get_slot_idx(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff815816b0)
Location: block/keyslot-manager.c:170
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_alloc_cipher_req
```
**Symbols:**

```
ffffffff81580e80-ffffffff81580eab: blk_ksm_get_slot_idx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_ksm_get_slot_idx(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8159e6e0)
Location: block/keyslot-manager.c:177
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_alloc_cipher_req
```
**Symbols:**

```
ffffffff8159dea0-ffffffff8159decb: blk_ksm_get_slot_idx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_ksm_get_slot_idx(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff815a5532)
Location: block/keyslot-manager.c:211
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_prepare_req
```
**Symbols:**

```
ffffffff815a4ae0-ffffffff815a4b00: blk_ksm_get_slot_idx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_ksm_get_slot_idx(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8160e002)
Location: block/keyslot-manager.c:211
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_prepare_req
```
**Symbols:**

```
ffffffff8160d490-ffffffff8160d4b0: blk_ksm_get_slot_idx (STB_GLOBAL)
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
