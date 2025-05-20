# Function: <code>scsi_16_lba_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815cfd90)
Location: drivers/ata/libata-scsi.c:1510
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
```
**Symbols:**

```
ffffffff815cfd90-ffffffff815cfdac: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816289c0)
Location: drivers/ata/libata-scsi.c:1585
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff816289c0-ffffffff816289dc: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81659630)
Location: drivers/ata/libata-scsi.c:1663
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff81659630-ffffffff8165964c: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8166df60)
Location: drivers/ata/libata-scsi.c:1654
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff8166df60-ffffffff8166df7c: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816d7590)
Location: drivers/ata/libata-scsi.c:1655
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff816d7590-ffffffff816d75ac: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81713f40)
Location: drivers/ata/libata-scsi.c:1658
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff81713f40-ffffffff81713f5c: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817363f0)
Location: drivers/ata/libata-scsi.c:1653
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff817363f0-ffffffff8173640c: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81772030)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff81772030-ffffffff81772050: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81795f90)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff81795f90-ffffffff81795fb0: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185a0e0)
Location: drivers/ata/libata-scsi.c:1346
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff8185a0e0-ffffffff8185a100: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81869200)
Location: drivers/ata/libata-scsi.c:1346
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff81869200-ffffffff81869220: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8184bc30)
Location: drivers/ata/libata-scsi.c:1342
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff8184bc30-ffffffff8184bc50: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818d9100)
Location: drivers/ata/libata-scsi.c:1344
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff818d9100-ffffffff818d9120: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2c170)
Location: drivers/ata/libata-scsi.c:1359
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81baf760)
Location: drivers/ata/libata-scsi.c:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c06db2)
Location: drivers/ata/libata-scsi.c:1384
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5be92)
Location: drivers/ata/libata-scsi.c:1336
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff80001099fa48)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffff80001099fa48-ffff80001099fa94: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a6fef4)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
c0a6fef4-c0a6ff2c: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a64090)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
c000000000a64090-c000000000a640b4: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe0005ff610)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffe0005ff610-ffffffe0005ff6a8: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8175b0a0)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff8175b0a0-ffffffff8175b0c0: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8173af40)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff8173af40-ffffffff8173af60: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8178ae10)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff8178ae10-ffffffff8178ae30: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_16_lba_len(const u8 *cdb, u64 *plba, u32 *plen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817a4c60)
Location: drivers/ata/libata-scsi.c:1636
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
**Symbols:**

```
ffffffff817a4c60-ffffffff817a4c80: scsi_16_lba_len (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
