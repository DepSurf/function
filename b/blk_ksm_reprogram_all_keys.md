# Function: <code>blk_ksm_reprogram_all_keys</code>

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
void blk_ksm_reprogram_all_keys(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff81580eb0)
Location: block/keyslot-manager.c:352
Inline: False
```
**Symbols:**

```
ffffffff81580eb0-ffffffff81580f26: blk_ksm_reprogram_all_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_ksm_reprogram_all_keys(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8159ded0)
Location: block/keyslot-manager.c:359
Inline: False
```
**Symbols:**

```
ffffffff8159ded0-ffffffff8159df46: blk_ksm_reprogram_all_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_ksm_reprogram_all_keys(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff815a4c50)
Location: block/keyslot-manager.c:407
Inline: True
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_set_initial_state
```
**Symbols:**

```
ffffffff815a4c50-ffffffff815a4cce: blk_ksm_reprogram_all_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_ksm_reprogram_all_keys(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8160d6c0)
Location: block/keyslot-manager.c:407
Inline: True
Direct callers:
  - drivers/mmc/core/crypto.c:mmc_crypto_set_initial_state
```
**Symbols:**

```
ffffffff8160d6c0-ffffffff8160d73e: blk_ksm_reprogram_all_keys (STB_GLOBAL)
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
