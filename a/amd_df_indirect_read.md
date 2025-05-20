# Function: <code>amd_df_indirect_read</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81066000)
Location: arch/x86/kernel/amd_nb.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81066000-ffffffff810660fe: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065370)
Location: arch/x86/kernel/amd_nb.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81065370-ffffffff81065444: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81069510)
Location: arch/x86/kernel/amd_nb.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81069510-ffffffff810695e4: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff8106c8e5-ffffffff8106c90b: amd_df_indirect_read.cold.4 (STB_LOCAL)
ffffffff8106c140-ffffffff8106c1fc: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81072775-ffffffff8107279b: amd_df_indirect_read.cold.4 (STB_LOCAL)
ffffffff81071ed0-ffffffff81071f8c: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81076280-ffffffff810762a8: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff81075a10-ffffffff81075ace: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81077250-ffffffff81077278: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff810769e0-ffffffff81076a9e: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff8107e580-ffffffff8107e5a8: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff8107dc80-ffffffff8107dd3e: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81bd7fc9-ffffffff81bd7ff1: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff8107d960-ffffffff8107da1e: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81bc9e7b-ffffffff81bc9ea3: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff8107ea90-ffffffff8107eb4f: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:200
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81c9efb1-ffffffff81c9efd9: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff8108d720-ffffffff8108d7dd: amd_df_indirect_read (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81076250-ffffffff81076278: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff810759e0-ffffffff81075a9e: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81066220-ffffffff81066248: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff810659d0-ffffffff81065a8e: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81076200-ffffffff81076228: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff81075990-ffffffff81075a4e: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 *lo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/kernel/amd_nb.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
  - arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr
```
**Symbols:**

```
ffffffff81078260-ffffffff81078288: amd_df_indirect_read.cold (STB_LOCAL)
ffffffff810779f0-ffffffff81077aae: amd_df_indirect_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
