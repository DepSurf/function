# Function: <code>dmar_iommu_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81539740)
Location: drivers/iommu/intel-iommu.c:4268
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81539740-ffffffff815399f6: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158e200)
Location: drivers/iommu/intel-iommu.c:4366
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff8158e200-ffffffff8158e4b6: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bbd00)
Location: drivers/iommu/intel-iommu.c:4470
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff815bbd00-ffffffff815bbfde: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d1940)
Location: drivers/iommu/intel-iommu.c:4465
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff815d1940-ffffffff815d1c1e: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81638710)
Location: drivers/iommu/intel-iommu.c:4371
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81638710-ffffffff816389fa: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4413
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81675714-ffffffff8167574a: dmar_iommu_hotplug.cold.94 (STB_LOCAL)
ffffffff81673a10-ffffffff81673ccb: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4422
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81693bb1-ffffffff81693be7: dmar_iommu_hotplug.cold.99 (STB_LOCAL)
ffffffff81691fe0-ffffffff8169225a: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4251
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816cc480-ffffffff816cc4b8: dmar_iommu_hotplug.cold (STB_LOCAL)
ffffffff816c9f60-ffffffff816ca20d: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4527
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816efccb-ffffffff816efd03: dmar_iommu_hotplug.cold (STB_LOCAL)
ffffffff816ecf30-ffffffff816ed1dd: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a5220)
Location: drivers/iommu/intel/iommu.c:4426
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff817a5220-ffffffff817a527e: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b2670)
Location: drivers/iommu/intel/iommu.c:3822
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff817b2670-ffffffff817b26ce: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81795560)
Location: drivers/iommu/intel/iommu.c:3912
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81795560-ffffffff817955be: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181d3d0)
Location: drivers/iommu/intel/iommu.c:3907
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff8181d3d0-ffffffff8181d42e: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195e150)
Location: drivers/iommu/intel/iommu.c:3618
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff8195e150-ffffffff8195e1be: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac5c80)
Location: drivers/iommu/intel/iommu.c:3494
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81ac5c80-ffffffff81ac5ce7: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b12730)
Location: drivers/iommu/intel/iommu.c:3381
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81b12730-ffffffff81b12797: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b66d10)
Location: drivers/iommu/intel/iommu.c:3230
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81b66d10-ffffffff81b66d77: dmar_iommu_hotplug (STB_GLOBAL)
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
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4527
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816b54b1-ffffffff816b54e9: dmar_iommu_hotplug.cold (STB_LOCAL)
ffffffff816b26a0-ffffffff816b294d: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4527
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816930fb-ffffffff81693133: dmar_iommu_hotplug.cold (STB_LOCAL)
ffffffff81690360-ffffffff8169060d: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4527
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816e398b-ffffffff816e39c3: dmar_iommu_hotplug.cold (STB_LOCAL)
ffffffff816e0bf0-ffffffff816e0e9d: dmar_iommu_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dmar_iommu_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4527
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816fe01b-ffffffff816fe06f: dmar_iommu_hotplug.cold (STB_LOCAL)
ffffffff816fb200-ffffffff816fb474: dmar_iommu_hotplug (STB_GLOBAL)
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
