# Function: <code>dmar_platform_optin</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168b440)
Location: drivers/iommu/dmar.c:2084
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8168b440-ffffffff8168b4a5: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816c2e70)
Location: drivers/iommu/dmar.c:2073
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816c2e70-ffffffff816c2edc: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816e5d60)
Location: drivers/iommu/dmar.c:2151
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816e5d60-ffffffff816e5dcc: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179c640)
Location: drivers/iommu/intel/dmar.c:2267
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/iommu.c:platform_optin_force_iommu
```
**Symbols:**

```
ffffffff8179c640-ffffffff8179c6aa: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817aa310)
Location: drivers/iommu/intel/dmar.c:2305
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/iommu.c:platform_optin_force_iommu
```
**Symbols:**

```
ffffffff817aa310-ffffffff817aa37a: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178d0b0)
Location: drivers/iommu/intel/dmar.c:2376
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8178d0b0-ffffffff8178d11a: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81814410)
Location: drivers/iommu/intel/dmar.c:2412
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81814410-ffffffff8181447a: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81955250)
Location: drivers/iommu/intel/dmar.c:2413
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81955250-ffffffff819552c6: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83ef4c09)
Location: drivers/iommu/intel/dmar.c:2402
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_capable
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81abb840-ffffffff81abb8b6: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8371a7c9)
Location: drivers/iommu/intel/dmar.c:2425
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_capable
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b08120-ffffffff81b08196: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8394e2a9)
Location: drivers/iommu/intel/dmar.c:2443
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_capable
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b5c140-ffffffff81b5c1b6: dmar_platform_optin (STB_GLOBAL)
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
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816ab840)
Location: drivers/iommu/dmar.c:2151
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816ab840-ffffffff816ab8ac: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816891a0)
Location: drivers/iommu/dmar.c:2151
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816891a0-ffffffff8168920c: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816d9a20)
Location: drivers/iommu/dmar.c:2151
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816d9a20-ffffffff816d9a8c: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dmar_platform_optin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816f3fd0)
Location: drivers/iommu/dmar.c:2151
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816f3fd0-ffffffff816f403c: dmar_platform_optin (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
