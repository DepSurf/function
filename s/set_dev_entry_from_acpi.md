# Function: <code>set_dev_entry_from_acpi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_dev_entry_from_acpi(struct amd_iommu *iommu, u16 devid, u32 flags, u32 ext_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81fa8a7c)
Location: drivers/iommu/amd_iommu_init.c:667
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff81fa8a7c-ffffffff81fa8b88: set_dev_entry_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd5379)
Location: drivers/iommu/amd_iommu_init.c:721
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff81fd5379-ffffffff81fd5485: set_dev_entry_from_acpi.constprop.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82013651)
Location: drivers/iommu/amd_iommu_init.c:823
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff82013651-ffffffff8201375d: set_dev_entry_from_acpi.constprop.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820f4a4a)
Location: drivers/iommu/amd_iommu_init.c:832
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff820f4a4a-ffffffff820f4b20: set_dev_entry_from_acpi.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826fe10a)
Location: drivers/iommu/amd_iommu_init.c:967
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff826fe10a-ffffffff826fe1e0: set_dev_entry_from_acpi.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8272840a)
Location: drivers/iommu/amd_iommu_init.c:967
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff8272840a-ffffffff827284a0: set_dev_entry_from_acpi.constprop.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e0737)
Location: drivers/iommu/amd_iommu_init.c:994
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff828e0737-ffffffff828e07cd: set_dev_entry_from_acpi.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828fb10f)
Location: drivers/iommu/amd_iommu_init.c:982
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff828fb10f-ffffffff828fb1a5: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82903f98)
Location: drivers/iommu/amd_iommu_init.c:983
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff82903f98-ffffffff8290402e: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1b724)
Location: drivers/iommu/amd/init.c:983
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff82d1b724-ffffffff82d1b7fd: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff830094f4)
Location: drivers/iommu/amd/init.c:1046
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff830094f4-ffffffff830095cd: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83213f6c)
Location: drivers/iommu/amd/init.c:1042
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff83213f6c-ffffffff83214042: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff832fd2ae)
Location: drivers/iommu/amd/init.c:1053
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff832fd2ae-ffffffff832fd384: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b5e9f)
Location: drivers/iommu/amd/init.c:1059
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff834b5e9f-ffffffff834b5f81: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef2080)
Location: drivers/iommu/amd/init.c:1157
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff83ef2080-ffffffff83ef21ea: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff83717cb0)
Location: drivers/iommu/amd/init.c:1192
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff83717cb0-ffffffff83717e1a: set_dev_entry_from_acpi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394b770)
Location: drivers/iommu/amd/init.c:1207
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
  - drivers/iommu/amd/init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff8394b770-ffffffff8394b8da: set_dev_entry_from_acpi.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828eb77f)
Location: drivers/iommu/amd_iommu_init.c:983
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff828eb77f-ffffffff828eb815: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e2c0c)
Location: drivers/iommu/amd_iommu_init.c:983
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff828e2c0c-ffffffff828e2ca2: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ff2bb)
Location: drivers/iommu/amd_iommu_init.c:983
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff828ff2bb-ffffffff828ff351: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82904ffa)
Location: drivers/iommu/amd_iommu_init.c:983
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
  - drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi
```
**Symbols:**

```
ffffffff82904ffa-ffffffff82905090: set_dev_entry_from_acpi.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
