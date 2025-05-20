# Function: <code>translation_pre_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:545
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:552
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:553
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:554
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826ff093)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:527
Inline: True
```
**Symbols:**

```
ffffffff81630aa0-ffffffff81630ab4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff827292ef)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272aa12)
Location: drivers/iommu/intel-iommu.c:529
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8166b950-ffffffff8166b964: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e153d)
Location: drivers/iommu/amd_iommu_init.c:273
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e32ea)
Location: drivers/iommu/intel-iommu.c:410
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168a090-ffffffff8168a0a4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828fc317)
Location: drivers/iommu/amd_iommu_init.c:258
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff816cb0aa)
Location: drivers/iommu/intel-iommu.c:404
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c18c0-ffffffff816c18d4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff829052d5)
Location: drivers/iommu/amd_iommu_init.c:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ee81f)
Location: drivers/iommu/intel-iommu.c:412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816e47e0-ffffffff816e47f4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1c0c6)
Location: drivers/iommu/amd/init.c:259
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a0522)
Location: drivers/iommu/intel/iommu.c:416
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8179a8d0-ffffffff8179a8e4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83009eb0)
Location: drivers/iommu/amd/init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b1a0b)
Location: drivers/iommu/intel/iommu.c:409
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817a8c00-ffffffff817a8c14: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832149e0)
Location: drivers/iommu/amd/init.c:262
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179474b)
Location: drivers/iommu/intel/iommu.c:418
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8178b780-ffffffff8178b794: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fdfcc)
Location: drivers/iommu/amd/init.c:263
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181c67b)
Location: drivers/iommu/intel/iommu.c:400
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81812fe0-ffffffff81812ff4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b6bd7)
Location: drivers/iommu/amd/init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff819580e9)
Location: drivers/iommu/intel/iommu.c:333
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81953f90-ffffffff81953faa: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef1e24)
Location: drivers/iommu/amd/init.c:236
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:init_iommu_one_late
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf139)
Location: drivers/iommu/intel/iommu.c:308
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ab9bd0-ffffffff81ab9bea: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83717a54)
Location: drivers/iommu/amd/init.c:239
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:init_iommu_one_late
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0bb29)
Location: drivers/iommu/intel/iommu.c:308
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b06080-ffffffff81b0609a: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394b4d4)
Location: drivers/iommu/amd/init.c:234
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:init_iommu_one_late
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b5fc09)
Location: drivers/iommu/intel/iommu.c:171
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b59e20-ffffffff81b59e3a: translation_pre_enabled (STB_GLOBAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ecabc)
Location: drivers/iommu/amd_iommu_init.c:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b3f8f)
Location: drivers/iommu/intel-iommu.c:412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816aa2c0-ffffffff816aa2d4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e3f49)
Location: drivers/iommu/amd_iommu_init.c:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691c4f)
Location: drivers/iommu/intel-iommu.c:412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81687c20-ffffffff81687c34: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff829005f8)
Location: drivers/iommu/amd_iommu_init.c:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e24df)
Location: drivers/iommu/intel-iommu.c:412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816d84a0-ffffffff816d84b4: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
bool translation_pre_enabled(struct amd_iommu *iommu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82906337)
Location: drivers/iommu/amd_iommu_init.c:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fcb3f)
Location: drivers/iommu/intel-iommu.c:412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f2a50-ffffffff816f2a64: translation_pre_enabled (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
