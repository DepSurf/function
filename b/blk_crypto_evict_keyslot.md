# Function: <code>blk_crypto_evict_keyslot</code>

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
void blk_crypto_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff81582d85)
Location: block/blk-crypto-fallback.c:90
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff81581ef0-ffffffff81581f51: blk_crypto_evict_keyslot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8159fc25)
Location: block/blk-crypto-fallback.c:90
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff8159eec0-ffffffff8159ef21: blk_crypto_evict_keyslot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff815a6a15)
Location: block/blk-crypto-fallback.c:91
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff815a5cd0-ffffffff815a5d31: blk_crypto_evict_keyslot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_evict_keyslot(unsigned int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8160f525)
Location: block/blk-crypto-fallback.c:91
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff8160e7e0-ffffffff8160e841: blk_crypto_evict_keyslot (STB_LOCAL)
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
