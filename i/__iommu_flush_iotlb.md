# Function: <code>__iommu_flush_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535dd0)
Location: drivers/iommu/intel-iommu.c:1383
Inline: False
```
**Symbols:**

```
ffffffff81535dd0-ffffffff81535fa6: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158a4e0)
Location: drivers/iommu/intel-iommu.c:1390
Inline: False
```
**Symbols:**

```
ffffffff8158a4e0-ffffffff8158a6f9: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b7b50)
Location: drivers/iommu/intel-iommu.c:1404
Inline: False
```
**Symbols:**

```
ffffffff815b7b50-ffffffff815b7d69: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cdc10)
Location: drivers/iommu/intel-iommu.c:1409
Inline: False
```
**Symbols:**

```
ffffffff815cdc10-ffffffff815cde05: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81634a50)
Location: drivers/iommu/intel-iommu.c:1392
Inline: False
```
**Symbols:**

```
ffffffff81634a50-ffffffff81634c45: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1394
Inline: False
```
**Symbols:**

```
ffffffff816703a0-ffffffff81670583: __iommu_flush_iotlb (STB_LOCAL)
ffffffff81675407-ffffffff8167542c: __iommu_flush_iotlb.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1270
Inline: False
```
**Symbols:**

```
ffffffff8168e4f0-ffffffff8168e6d3: __iommu_flush_iotlb (STB_LOCAL)
ffffffff8169384e-ffffffff81693873: __iommu_flush_iotlb.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1275
Inline: False
```
**Symbols:**

```
ffffffff816c5b30-ffffffff816c5d0e: __iommu_flush_iotlb (STB_LOCAL)
ffffffff816cbd11-ffffffff816cbd36: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1286
Inline: False
```
**Symbols:**

```
ffffffff816e8b60-ffffffff816e8d3e: __iommu_flush_iotlb (STB_LOCAL)
ffffffff816ef617-ffffffff816ef63c: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1302
Inline: False
```
**Symbols:**

```
ffffffff8179fb60-ffffffff8179fd4a: __iommu_flush_iotlb (STB_LOCAL)
ffffffff817a6a01-ffffffff817a6a26: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1385
Inline: False
```
**Symbols:**

```
ffffffff817ad700-ffffffff817ad8ea: __iommu_flush_iotlb (STB_LOCAL)
ffffffff81c0c337-ffffffff81c0c35c: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1409
Inline: False
```
**Symbols:**

```
ffffffff81790090-ffffffff81790279: __iommu_flush_iotlb (STB_LOCAL)
ffffffff81bfdba1-ffffffff81bfdbc6: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1413
Inline: False
```
**Symbols:**

```
ffffffff81817900-ffffffff81817ae9: __iommu_flush_iotlb (STB_LOCAL)
ffffffff81cff22a-ffffffff81cff24f: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1343
Inline: False
```
**Symbols:**

```
ffffffff819588a0-ffffffff81958ad2: __iommu_flush_iotlb (STB_LOCAL)
ffffffff81ec7a39-ffffffff81ec7a5e: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81abfa00)
Location: drivers/iommu/intel/iommu.c:1298
Inline: False
```
**Symbols:**

```
ffffffff81abfa00-ffffffff81abfc4e: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0c260)
Location: drivers/iommu/intel/iommu.c:1299
Inline: False
```
**Symbols:**

```
ffffffff81b0c260-ffffffff81b0c4c9: __iommu_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b60a10)
Location: drivers/iommu/intel/iommu.c:1159
Inline: False
```
**Symbols:**

```
ffffffff81b60a10-ffffffff81b60c79: __iommu_flush_iotlb (STB_LOCAL)
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
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1286
Inline: False
```
**Symbols:**

```
ffffffff816ae640-ffffffff816ae81e: __iommu_flush_iotlb (STB_LOCAL)
ffffffff816b4e07-ffffffff816b4e2c: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1286
Inline: False
```
**Symbols:**

```
ffffffff8168bfa0-ffffffff8168c17e: __iommu_flush_iotlb (STB_LOCAL)
ffffffff81692a47-ffffffff81692a6c: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1286
Inline: False
```
**Symbols:**

```
ffffffff816dc820-ffffffff816dc9fe: __iommu_flush_iotlb (STB_LOCAL)
ffffffff816e32d7-ffffffff816e32fc: __iommu_flush_iotlb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __iommu_flush_iotlb(struct intel_iommu *iommu, u16 did, u64 addr, unsigned int size_order, u64 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1286
Inline: False
```
**Symbols:**

```
ffffffff816f6e60-ffffffff816f703e: __iommu_flush_iotlb (STB_LOCAL)
ffffffff816fd967-ffffffff816fd98c: __iommu_flush_iotlb.cold (STB_LOCAL)
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
