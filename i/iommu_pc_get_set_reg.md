# Function: <code>iommu_pc_get_set_reg</code>

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
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca270)
Location: drivers/iommu/amd_iommu_init.c:2792
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff815ca270-ffffffff815ca341: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630c60)
Location: drivers/iommu/amd_iommu_init.c:2989
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81630c60-ffffffff81630d30: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bb10)
Location: drivers/iommu/amd_iommu_init.c:2990
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8166bb10-ffffffff8166bbe2: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a260)
Location: drivers/iommu/amd_iommu_init.c:3026
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8168a260-ffffffff8168a332: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:3100
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816c1c10-ffffffff816c1ce7: iommu_pc_get_set_reg (STB_LOCAL)
ffffffff816c28f2-ffffffff816c290a: iommu_pc_get_set_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4b30)
Location: drivers/iommu/amd_iommu_init.c:3131
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816e4b30-ffffffff816e4c05: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179abf0)
Location: drivers/iommu/amd/init.c:3101
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8179abf0-ffffffff8179acbc: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a8f10)
Location: drivers/iommu/amd/init.c:3316
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
```
**Symbols:**

```
ffffffff817a8f10-ffffffff817a8fdc: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178ac60)
Location: drivers/iommu/amd/init.c:3263
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
```
**Symbols:**

```
ffffffff8178ac60-ffffffff8178ad28: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3303
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
```
**Symbols:**

```
ffffffff81811f10-ffffffff81812019: iommu_pc_get_set_reg (STB_LOCAL)
ffffffff81cfe59f-ffffffff81cfe5d6: iommu_pc_get_set_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3313
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
```
**Symbols:**

```
ffffffff81952dc0-ffffffff81952efd: iommu_pc_get_set_reg (STB_LOCAL)
ffffffff81ec6dae-ffffffff81ec6de5: iommu_pc_get_set_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3614
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
```
**Symbols:**

```
ffffffff81ab86c0-ffffffff81ab87fd: iommu_pc_get_set_reg (STB_LOCAL)
ffffffff8209709c-ffffffff820970d3: iommu_pc_get_set_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3694
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
```
**Symbols:**

```
ffffffff81b04a30-ffffffff81b04b6d: iommu_pc_get_set_reg (STB_LOCAL)
ffffffff82117fbd-ffffffff82117ff4: iommu_pc_get_set_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3716
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_reg
```
**Symbols:**

```
ffffffff81b587f0-ffffffff81b5892d: iommu_pc_get_set_reg (STB_LOCAL)
ffffffff821f5be5-ffffffff821f5c1c: iommu_pc_get_set_reg.cold (STB_LOCAL)
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
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa610)
Location: drivers/iommu/amd_iommu_init.c:3131
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816aa610-ffffffff816aa6e5: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81687e00)
Location: drivers/iommu/amd_iommu_init.c:3131
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81687e00-ffffffff81687ed5: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d87f0)
Location: drivers/iommu/amd_iommu_init.c:3131
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816d87f0-ffffffff816d88c5: iommu_pc_get_set_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu *iommu, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2da0)
Location: drivers/iommu/amd_iommu_init.c:3131
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816f2da0-ffffffff816f2e75: iommu_pc_get_set_reg (STB_LOCAL)
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
