# Function: <code>blk_ksm_destroy</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (ffffffff81581183)
Location: block/keyslot-manager.c:372
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
Direct callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
**Symbols:**

```
ffffffff81580f60-ffffffff81580fcb: blk_ksm_destroy.part.0 (STB_LOCAL)
ffffffff81580fd0-ffffffff81580fe6: blk_ksm_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (ffffffff8159e1ba)
Location: block/keyslot-manager.c:379
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
Direct callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
**Symbols:**

```
ffffffff8159df80-ffffffff8159dfeb: blk_ksm_destroy.part.0 (STB_LOCAL)
ffffffff8159dff0-ffffffff8159e006: blk_ksm_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (ffffffff815a4ef6)
Location: block/keyslot-manager.c:430
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
Direct callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff815a4cd0-ffffffff815a4d3b: blk_ksm_destroy.part.0 (STB_LOCAL)
ffffffff815a4d40-ffffffff815a4d56: blk_ksm_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (ffffffff8160d97a)
Location: block/keyslot-manager.c:430
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
Direct callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8160d740-ffffffff8160d7ab: blk_ksm_destroy.part.0 (STB_LOCAL)
ffffffff8160d7b0-ffffffff8160d7c6: blk_ksm_destroy (STB_GLOBAL)
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
