# Function: <code>copy_device_table</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81631275)
Location: drivers/iommu/amd_iommu_init.c:856
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166c135)
Location: drivers/iommu/amd_iommu_init.c:856
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff8168a9b5)
Location: drivers/iommu/amd_iommu_init.c:873
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff816c23f5)
Location: drivers/iommu/amd_iommu_init.c:861
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff816e5315)
Location: drivers/iommu/amd_iommu_init.c:862
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool copy_device_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:862
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8179ad80-ffffffff8179adb4: copy_device_table (STB_LOCAL)
ffffffff8179baf5-ffffffff8179bd39: copy_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool copy_device_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:925
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff817a90a0-ffffffff817a90d4: copy_device_table (STB_LOCAL)
ffffffff81c0b8fa-ffffffff81c0bb4a: copy_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool copy_device_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:921
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8178ad90-ffffffff8178adc2: copy_device_table (STB_LOCAL)
ffffffff81bfd2bc-ffffffff81bfd50f: copy_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool copy_device_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:932
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81812020-ffffffff8181205c: copy_device_table (STB_LOCAL)
ffffffff81cfe5d6-ffffffff81cfe83f: copy_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool copy_device_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:936
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81952f00-ffffffff81952f32: copy_device_table (STB_LOCAL)
ffffffff81ec6de5-ffffffff81ec708b: copy_device_table.cold (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff81ab9698)
Location: drivers/iommu/amd/init.c:1115
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b05b08)
Location: drivers/iommu/amd/init.c:1150
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b598a8)
Location: drivers/iommu/amd/init.c:1165
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff816aadf5)
Location: drivers/iommu/amd_iommu_init.c:862
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff81688755)
Location: drivers/iommu/amd_iommu_init.c:862
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff816d8fd5)
Location: drivers/iommu/amd_iommu_init.c:862
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff816f3585)
Location: drivers/iommu/amd_iommu_init.c:862
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
</ul>
