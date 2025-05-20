# Function: <code>intel_iommu_add</code>

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
In drivers/iommu/intel-iommu.c (ffffffff8153977d)
Location: drivers/iommu/intel-iommu.c:4186
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
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
In drivers/iommu/intel-iommu.c (ffffffff8158e24a)
Location: drivers/iommu/intel-iommu.c:4284
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
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
In drivers/iommu/intel-iommu.c (ffffffff815bbd58)
Location: drivers/iommu/intel-iommu.c:4388
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
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
In drivers/iommu/intel-iommu.c (ffffffff815d1998)
Location: drivers/iommu/intel-iommu.c:4383
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81638768)
Location: drivers/iommu/intel-iommu.c:4289
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81673a68)
Location: drivers/iommu/intel-iommu.c:4331
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8169203a)
Location: drivers/iommu/intel-iommu.c:4340
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c9fbc)
Location: drivers/iommu/intel-iommu.c:4169
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ecf8c)
Location: drivers/iommu/intel-iommu.c:4445
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4347
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff817a4ca0-ffffffff817a4eec: intel_iommu_add (STB_LOCAL)
ffffffff817a739e-ffffffff817a73d6: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3743
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff817b2130-ffffffff817b2333: intel_iommu_add (STB_LOCAL)
ffffffff81c0cbe3-ffffffff81c0cc37: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3831
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff81794ed0-ffffffff81795093: intel_iommu_add (STB_LOCAL)
ffffffff81bfe33a-ffffffff81bfe38e: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3826
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff8181cd30-ffffffff8181cf18: intel_iommu_add (STB_LOCAL)
ffffffff81d00168-ffffffff81d001db: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3542
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff8195db00-ffffffff8195dcb6: intel_iommu_add (STB_LOCAL)
ffffffff81ec8826-ffffffff81ec8873: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3422
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff81ac5460-ffffffff81ac568c: intel_iommu_add (STB_LOCAL)
ffffffff82097aa4-ffffffff82097ac3: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3309
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff81b11ed0-ffffffff81b120ca: intel_iommu_add (STB_LOCAL)
ffffffff82118a11-ffffffff82118a2a: intel_iommu_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_iommu_add(struct dmar_drhd_unit *dmaru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3158
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
```
**Symbols:**

```
ffffffff81b65c40-ffffffff81b65e3c: intel_iommu_add (STB_LOCAL)
ffffffff821f6710-ffffffff821f6729: intel_iommu_add.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b26fc)
Location: drivers/iommu/intel-iommu.c:4445
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816903bc)
Location: drivers/iommu/intel-iommu.c:4445
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e0c4c)
Location: drivers/iommu/intel-iommu.c:4445
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fb25c)
Location: drivers/iommu/intel-iommu.c:4445
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
