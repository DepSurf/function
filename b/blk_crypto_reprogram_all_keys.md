# Function: <code>blk_crypto_reprogram_all_keys</code>

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
void blk_crypto_reprogram_all_keys(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c2000)
Location: block/blk-crypto-profile.c:420
Inline: True
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_set_initial_state
```
**Symbols:**

```
ffffffff816c2000-ffffffff816c209e: blk_crypto_reprogram_all_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_reprogram_all_keys(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817832f0)
Location: block/blk-crypto-profile.c:421
Inline: True
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_set_initial_state
```
**Symbols:**

```
ffffffff817832f0-ffffffff8178338e: blk_crypto_reprogram_all_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_reprogram_all_keys(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c35a0)
Location: block/blk-crypto-profile.c:418
Inline: True
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_set_initial_state
```
**Symbols:**

```
ffffffff817c35a0-ffffffff817c3643: blk_crypto_reprogram_all_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_crypto_reprogram_all_keys(struct blk_crypto_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81808230)
Location: block/blk-crypto-profile.c:418
Inline: True
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_set_initial_state
```
**Symbols:**

```
ffffffff81808230-ffffffff818082d3: blk_crypto_reprogram_all_keys (STB_GLOBAL)
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
