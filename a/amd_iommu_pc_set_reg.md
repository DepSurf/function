# Function: <code>amd_iommu_pc_set_reg</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca380)
Location: drivers/iommu/amd_iommu_init.c:2839
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff815ca380-ffffffff815ca3ab: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630d60)
Location: drivers/iommu/amd_iommu_init.c:3036
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81630d60-ffffffff81630d8b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bc20)
Location: drivers/iommu/amd_iommu_init.c:3037
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff8166bc20-ffffffff8166bc4b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a370)
Location: drivers/iommu/amd_iommu_init.c:3073
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff8168a370-ffffffff8168a39b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1d20)
Location: drivers/iommu/amd_iommu_init.c:3147
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff816c1d20-ffffffff816c1d4b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4c40)
Location: drivers/iommu/amd_iommu_init.c:3178
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff816e4c40-ffffffff816e4c6b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179acf0)
Location: drivers/iommu/amd/init.c:3148
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
```
**Symbols:**

```
ffffffff8179acf0-ffffffff8179ad1b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9010)
Location: drivers/iommu/amd/init.c:3363
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
  - arch/x86/events/amd/iommu.c:perf_iommu_enable_event
```
**Symbols:**

```
ffffffff817a9010-ffffffff817a903b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178bc20)
Location: drivers/iommu/amd/init.c:3309
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff8178bc20-ffffffff8178bc4b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81813210)
Location: drivers/iommu/amd/init.c:3349
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81813210-ffffffff8181323b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff819541d0)
Location: drivers/iommu/amd/init.c:3359
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff819541d0-ffffffff8195421f: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab9eb0)
Location: drivers/iommu/amd/init.c:3660
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81ab9eb0-ffffffff81ab9eff: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b06450)
Location: drivers/iommu/amd/init.c:3740
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81b06450-ffffffff81b0649f: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b5a260)
Location: drivers/iommu/amd/init.c:3762
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81b5a260-ffffffff81b5a2af: amd_iommu_pc_set_reg (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa720)
Location: drivers/iommu/amd_iommu_init.c:3178
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff816aa720-ffffffff816aa74b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81687f10)
Location: drivers/iommu/amd_iommu_init.c:3178
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81687f10-ffffffff81687f3b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8900)
Location: drivers/iommu/amd_iommu_init.c:3178
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff816d8900-ffffffff816d892b: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2eb0)
Location: drivers/iommu/amd_iommu_init.c:3178
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff816f2eb0-ffffffff816f2edb: amd_iommu_pc_set_reg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
