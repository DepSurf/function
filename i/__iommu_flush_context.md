# Function: <code>__iommu_flush_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535fb0)
Location: drivers/iommu/intel-iommu.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81535fb0-ffffffff815360b8: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158a700)
Location: drivers/iommu/intel-iommu.c:1356
Inline: False
```
**Symbols:**

```
ffffffff8158a700-ffffffff8158a833: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b7d70)
Location: drivers/iommu/intel-iommu.c:1370
Inline: False
```
**Symbols:**

```
ffffffff815b7d70-ffffffff815b7ea3: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cde10)
Location: drivers/iommu/intel-iommu.c:1375
Inline: False
```
**Symbols:**

```
ffffffff815cde10-ffffffff815cdf1d: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81634c50)
Location: drivers/iommu/intel-iommu.c:1358
Inline: False
```
**Symbols:**

```
ffffffff81634c50-ffffffff81634d5d: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1360
Inline: False
```
**Symbols:**

```
ffffffff8166ffd0-ffffffff816700d8: __iommu_flush_context (STB_LOCAL)
ffffffff816753d7-ffffffff816753e3: __iommu_flush_context.cold.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1236
Inline: False
```
**Symbols:**

```
ffffffff8168e6e0-ffffffff8168e7e8: __iommu_flush_context (STB_LOCAL)
ffffffff81693873-ffffffff8169387f: __iommu_flush_context.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1241
Inline: False
```
**Symbols:**

```
ffffffff816c5d10-ffffffff816c5e18: __iommu_flush_context (STB_LOCAL)
ffffffff816cbd36-ffffffff816cbd42: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1252
Inline: False
```
**Symbols:**

```
ffffffff816e8d40-ffffffff816e8e48: __iommu_flush_context (STB_LOCAL)
ffffffff816ef63c-ffffffff816ef648: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1268
Inline: False
```
**Symbols:**

```
ffffffff8179fd50-ffffffff8179fe5b: __iommu_flush_context (STB_LOCAL)
ffffffff817a6a26-ffffffff817a6a32: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1351
Inline: False
```
**Symbols:**

```
ffffffff817ad8f0-ffffffff817ad9fb: __iommu_flush_context (STB_LOCAL)
ffffffff81c0c35c-ffffffff81c0c368: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1375
Inline: False
```
**Symbols:**

```
ffffffff81790280-ffffffff81790393: __iommu_flush_context (STB_LOCAL)
ffffffff81bfdbc6-ffffffff81bfdbd2: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81817af0-ffffffff81817bf9: __iommu_flush_context (STB_LOCAL)
ffffffff81cff24f-ffffffff81cff25b: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1309
Inline: False
```
**Symbols:**

```
ffffffff81958ae0-ffffffff81958bfa: __iommu_flush_context (STB_LOCAL)
ffffffff81ec7a5e-ffffffff81ec7a6a: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81abfc60)
Location: drivers/iommu/intel/iommu.c:1264
Inline: False
```
**Symbols:**

```
ffffffff81abfc60-ffffffff81abfd83: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0c4e0)
Location: drivers/iommu/intel/iommu.c:1263
Inline: False
```
**Symbols:**

```
ffffffff81b0c4e0-ffffffff81b0c633: __iommu_flush_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b60c90)
Location: drivers/iommu/intel/iommu.c:1123
Inline: False
```
**Symbols:**

```
ffffffff81b60c90-ffffffff81b60de3: __iommu_flush_context (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1252
Inline: False
```
**Symbols:**

```
ffffffff816ae820-ffffffff816ae928: __iommu_flush_context (STB_LOCAL)
ffffffff816b4e2c-ffffffff816b4e38: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1252
Inline: False
```
**Symbols:**

```
ffffffff8168c180-ffffffff8168c288: __iommu_flush_context (STB_LOCAL)
ffffffff81692a6c-ffffffff81692a78: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1252
Inline: False
```
**Symbols:**

```
ffffffff816dca00-ffffffff816dcb08: __iommu_flush_context (STB_LOCAL)
ffffffff816e32fc-ffffffff816e3308: __iommu_flush_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_context(struct intel_iommu *iommu, u16 did, u16 source_id, u8 function_mask, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1252
Inline: False
```
**Symbols:**

```
ffffffff816f7040-ffffffff816f7148: __iommu_flush_context (STB_LOCAL)
ffffffff816fd98c-ffffffff816fd998: __iommu_flush_context.cold (STB_LOCAL)
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
