# Function: <code>iosf_mbi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107a540)
Location: arch/x86/platform/intel/iosf_mbi.c:124
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff8107a540-ffffffff8107a5d1: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107be00)
Location: arch/x86/platform/intel/iosf_mbi.c:124
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff8107be00-ffffffff8107be9a: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810803a0)
Location: arch/x86/platform/intel/iosf_mbi.c:124
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810803a0-ffffffff8108043a: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107e780)
Location: arch/x86/platform/intel/iosf_mbi.c:126
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
```
**Symbols:**

```
ffffffff8107e780-ffffffff8107e806: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81084fb0)
Location: arch/x86/platform/intel/iosf_mbi.c:126
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
```
**Symbols:**

```
ffffffff81084fb0-ffffffff81085036: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088380)
Location: arch/x86/platform/intel/iosf_mbi.c:126
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
```
**Symbols:**

```
ffffffff81088380-ffffffff81088404: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fc40)
Location: arch/x86/platform/intel/iosf_mbi.c:128
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
**Symbols:**

```
ffffffff8108fc40-ffffffff8108fcc4: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093c3a)
Location: arch/x86/platform/intel/iosf_mbi.c:119
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
**Symbols:**

```
ffffffff81093c3a-ffffffff81093c51: iosf_mbi_write.cold (STB_LOCAL)
ffffffff810938a0-ffffffff81093920: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81094690)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81094690-ffffffff81094716: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099950)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81099950-ffffffff810999d6: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098a40)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81098a40-ffffffff81098ac6: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099280)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81099280-ffffffff81099306: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a8f00)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810a8f00-ffffffff810a8f86: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810beef7)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810be670-ffffffff810be706: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810dab27)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810da1b0-ffffffff810da246: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e60b7)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810e5740-ffffffff810e57d6: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee4a7)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810edb30-ffffffff810edbc6: iosf_mbi_write (STB_GLOBAL)
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
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093650)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81093650-ffffffff810936d6: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810820e0)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff810820e0-ffffffff81082166: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093600)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81093600-ffffffff81093686: iosf_mbi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_write(u8 port, u8 opcode, u32 offset, u32 mdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095b50)
Location: arch/x86/platform/intel/iosf_mbi.c:120
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:mcr_set
```
**Symbols:**

```
ffffffff81095b50-ffffffff81095bd6: iosf_mbi_write (STB_GLOBAL)
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
