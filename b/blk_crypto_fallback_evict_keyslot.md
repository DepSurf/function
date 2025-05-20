# Function: <code>blk_crypto_fallback_evict_keyslot</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_fallback_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff816c3e35)
Location: block/blk-crypto-fallback.c:92
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff816c2f40-ffffffff816c2fb7: blk_crypto_fallback_evict_keyslot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_fallback_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff81785315)
Location: block/blk-crypto-fallback.c:92
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff81784390-ffffffff81784407: blk_crypto_fallback_evict_keyslot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_fallback_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff817c5665)
Location: block/blk-crypto-fallback.c:92
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff817c4680-ffffffff817c470b: blk_crypto_fallback_evict_keyslot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_fallback_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8180a355)
Location: block/blk-crypto-fallback.c:92
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff81809340-ffffffff818093cb: blk_crypto_fallback_evict_keyslot (STB_LOCAL)
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
