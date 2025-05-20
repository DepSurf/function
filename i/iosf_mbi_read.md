# Function: <code>iosf_mbi_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107a5e0)
Location: arch/x86/platform/intel/iosf_mbi.c:101
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff8107a5e0-ffffffff8107a671: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107bea0)
Location: arch/x86/platform/intel/iosf_mbi.c:101
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff8107bea0-ffffffff8107bf3a: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81080440)
Location: arch/x86/platform/intel/iosf_mbi.c:101
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81080440-ffffffff810804da: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107e6f0)
Location: arch/x86/platform/intel/iosf_mbi.c:103
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
```
**Symbols:**

```
ffffffff8107e6f0-ffffffff8107e776: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81084f20)
Location: arch/x86/platform/intel/iosf_mbi.c:103
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
```
**Symbols:**

```
ffffffff81084f20-ffffffff81084fa6: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810882f0)
Location: arch/x86/platform/intel/iosf_mbi.c:103
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
```
**Symbols:**

```
ffffffff810882f0-ffffffff81088374: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fb50)
Location: arch/x86/platform/intel/iosf_mbi.c:105
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff8108fb50-ffffffff8108fbd4: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093bfe)
Location: arch/x86/platform/intel/iosf_mbi.c:96
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff81093bfe-ffffffff81093c15: iosf_mbi_read.cold (STB_LOCAL)
ffffffff810937e0-ffffffff81093860: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810945c0)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff810945c0-ffffffff81094646: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810998c0)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810998c0-ffffffff81099946: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810989b0)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810989b0-ffffffff81098a36: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810991f0)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810991f0-ffffffff81099276: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a8de0)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810a8de0-ffffffff810a8e66: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810bef7f)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810be540-ffffffff810be5d6: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810dabb5)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810da020-ffffffff810da0b6: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e6145)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810e55b0-ffffffff810e5646: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee538)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810ed9a0-ffffffff810eda36: iosf_mbi_read (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093580)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff81093580-ffffffff81093606: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81082010)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff81082010-ffffffff81082096: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093530)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff81093530-ffffffff810935b6: iosf_mbi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_read(u8 port, u8 opcode, u32 offset, u32 *mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095a80)
Location: arch/x86/platform/intel/iosf_mbi.c:97
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_get_sem
```
**Symbols:**

```
ffffffff81095a80-ffffffff81095b06: iosf_mbi_read (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
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
