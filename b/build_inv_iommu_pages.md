# Function: <code>build_inv_iommu_pages</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152f4d5)
Location: drivers/iommu/amd_iommu.c:714
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
In drivers/iommu/amd_iommu.c (ffffffff81582dc1)
Location: drivers/iommu/amd_iommu.c:810
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
In drivers/iommu/amd_iommu.c (ffffffff815b00f1)
Location: drivers/iommu/amd_iommu.c:880
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3f60)
Location: drivers/iommu/amd_iommu.c:938
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff815c3f60-ffffffff815c3fca: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162acb0)
Location: drivers/iommu/amd_iommu.c:879
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8162acb0-ffffffff8162ad1a: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816658d0)
Location: drivers/iommu/amd_iommu.c:885
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816658d0-ffffffff8166593f: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684340)
Location: drivers/iommu/amd_iommu.c:900
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81684340-ffffffff816843af: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb8a0)
Location: drivers/iommu/amd_iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816bb8a0-ffffffff816bb904: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de730)
Location: drivers/iommu/amd_iommu.c:895
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816de730-ffffffff816de794: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798ba2)
Location: drivers/iommu/amd/iommu.c:839
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81794ea0-ffffffff81794f04: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a742d)
Location: drivers/iommu/amd/iommu.c:930
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff817a3360-ffffffff817a33c4: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81788d75)
Location: drivers/iommu/amd/iommu.c:896
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81810a07)
Location: drivers/iommu/amd/iommu.c:908
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
**Symbols:**

```
ffffffff8180d670-ffffffff8180d708: build_inv_iommu_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194eac1)
Location: drivers/iommu/amd/iommu.c:930
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab3397)
Location: drivers/iommu/amd/iommu.c:999
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81affe70)
Location: drivers/iommu/amd/iommu.c:1016
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81affe70-ffffffff81afff25: build_inv_iommu_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, ioasid_t pasid, bool gn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b533a0)
Location: drivers/iommu/amd/iommu.c:1129
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81b533a0-ffffffff81b53473: build_inv_iommu_pages (STB_LOCAL)
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
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4180)
Location: drivers/iommu/amd_iommu.c:895
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816a4180-ffffffff816a41e4: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681b70)
Location: drivers/iommu/amd_iommu.c:895
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81681b70-ffffffff81681bd4: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d23f0)
Location: drivers/iommu/amd_iommu.c:895
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816d23f0-ffffffff816d2454: build_inv_iommu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd *cmd, u64 address, size_t size, u16 domid, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eca30)
Location: drivers/iommu/amd_iommu.c:895
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816eca30-ffffffff816eca94: build_inv_iommu_pages (STB_LOCAL)
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
