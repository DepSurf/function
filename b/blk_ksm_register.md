# Function: <code>blk_ksm_register</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager *ksm, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (0)
Location: block/keyslot-manager.c:382
Inline: False
```
**Symbols:**

```
ffffffff81581776-ffffffff81581789: blk_ksm_register.cold (STB_LOCAL)
ffffffff81580f30-ffffffff81580f55: blk_ksm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager *ksm, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (0)
Location: block/keyslot-manager.c:389
Inline: False
```
**Symbols:**

```
ffffffff81bf3f0d-ffffffff81bf3f20: blk_ksm_register.cold (STB_LOCAL)
ffffffff8159df50-ffffffff8159df75: blk_ksm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager *ksm, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (0)
Location: block/keyslot-manager.c:440
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/crypto.c:mmc_crypto_setup_queue
```
**Symbols:**

```
ffffffff81be5d67-ffffffff81be5d7b: blk_ksm_register.cold (STB_LOCAL)
ffffffff815a4b60-ffffffff815a4b80: blk_ksm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager *ksm, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (0)
Location: block/keyslot-manager.c:440
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/crypto.c:mmc_crypto_setup_queue
```
**Symbols:**

```
ffffffff81cda5e8-ffffffff81cda5fc: blk_ksm_register.cold (STB_LOCAL)
ffffffff8160d510-ffffffff8160d530: blk_ksm_register (STB_GLOBAL)
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
