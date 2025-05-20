# Function: <code>amd_iommu_pc_get_reg</code>

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
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca350)
Location: drivers/iommu/amd_iommu_init.c:2830
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff815ca350-ffffffff815ca378: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630d30)
Location: drivers/iommu/amd_iommu_init.c:3027
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff81630d30-ffffffff81630d58: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bbf0)
Location: drivers/iommu/amd_iommu_init.c:3028
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff8166bbf0-ffffffff8166bc18: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a340)
Location: drivers/iommu/amd_iommu_init.c:3064
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff8168a340-ffffffff8168a368: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1cf0)
Location: drivers/iommu/amd_iommu_init.c:3138
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff816c1cf0-ffffffff816c1d18: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4c10)
Location: drivers/iommu/amd_iommu_init.c:3169
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff816e4c10-ffffffff816e4c38: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179acc0)
Location: drivers/iommu/amd/init.c:3139
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff8179acc0-ffffffff8179ace8: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a8fe0)
Location: drivers/iommu/amd/init.c:3354
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff817a8fe0-ffffffff817a9008: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178bbf0)
Location: drivers/iommu/amd/init.c:3301
Inline: False
```
**Symbols:**

```
ffffffff8178bbf0-ffffffff8178bc18: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff818131e0)
Location: drivers/iommu/amd/init.c:3341
Inline: False
```
**Symbols:**

```
ffffffff818131e0-ffffffff81813208: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81954180)
Location: drivers/iommu/amd/init.c:3351
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff81954180-ffffffff819541cc: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab9e50)
Location: drivers/iommu/amd/init.c:3652
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff81ab9e50-ffffffff81ab9e9c: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b063f0)
Location: drivers/iommu/amd/init.c:3732
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff81b063f0-ffffffff81b0643c: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b5a200)
Location: drivers/iommu/amd/init.c:3754
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff81b5a200-ffffffff81b5a24c: amd_iommu_pc_get_reg (STB_GLOBAL)
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
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa6f0)
Location: drivers/iommu/amd_iommu_init.c:3169
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff816aa6f0-ffffffff816aa718: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81687ee0)
Location: drivers/iommu/amd_iommu_init.c:3169
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff81687ee0-ffffffff81687f08: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d88d0)
Location: drivers/iommu/amd_iommu_init.c:3169
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff816d88d0-ffffffff816d88f8: amd_iommu_pc_get_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int amd_iommu_pc_get_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2e80)
Location: drivers/iommu/amd_iommu_init.c:3169
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
**Symbols:**

```
ffffffff816f2e80-ffffffff816f2ea8: amd_iommu_pc_get_reg (STB_GLOBAL)
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
