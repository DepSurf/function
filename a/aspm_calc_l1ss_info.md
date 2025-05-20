# Function: <code>aspm_calc_l1ss_info</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814c0808)
Location: drivers/pci/pcie/aspm.c:440
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff81500b7c)
Location: drivers/pci/pcie/aspm.c:455
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff81532908)
Location: drivers/pci/pcie/aspm.c:480
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff81549d24)
Location: drivers/pci/pcie/aspm.c:478
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff81579b28)
Location: drivers/pci/pcie/aspm.c:493
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
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
In drivers/pci/pcie/aspm.c (ffffffff8159b257)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state *link, struct aspm_register_info *upreg, struct aspm_register_info *dwreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:497
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81639fd0-ffffffff8163a1d6: aspm_calc_l1ss_info (STB_LOCAL)
ffffffff8163b834-ffffffff8163b923: aspm_calc_l1ss_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state *link, u32 parent_l1ss_cap, u32 child_l1ss_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:452
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81661a60-ffffffff81661e63: aspm_calc_l1ss_info (STB_LOCAL)
ffffffff81bf9014-ffffffff81bf9107: aspm_calc_l1ss_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state *link, u32 parent_l1ss_cap, u32 child_l1ss_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:452
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81643e30-ffffffff81644220: aspm_calc_l1ss_info (STB_LOCAL)
ffffffff81beae4d-ffffffff81beaf3f: aspm_calc_l1ss_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state *link, u32 parent_l1ss_cap, u32 child_l1ss_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:452
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff816b4bd0-ffffffff816b4fc0: aspm_calc_l1ss_info (STB_LOCAL)
ffffffff81ce5d8d-ffffffff81ce5e7f: aspm_calc_l1ss_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state *link, u32 parent_l1ss_cap, u32 child_l1ss_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:459
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff817d8410-ffffffff817d88aa: aspm_calc_l1ss_info (STB_LOCAL)
ffffffff81eac7c7-ffffffff81eac8d8: aspm_calc_l1ss_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state *link, u32 parent_l1ss_cap, u32 child_l1ss_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff818f9af0)
Location: drivers/pci/pcie/aspm.c:474
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
```
**Symbols:**

```
ffffffff818f9af0-ffffffff818fa0cc: aspm_calc_l1ss_info (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010702c68)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c089a6f0)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d167c)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
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
In drivers/pci/pcie/aspm.c (ffffffff8158f0e7)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
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
In drivers/pci/pcie/aspm.c (ffffffff8157dc27)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
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
In drivers/pci/pcie/aspm.c (ffffffff8158efa7)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
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
In drivers/pci/pcie/aspm.c (ffffffff815a9457)
Location: drivers/pci/pcie/aspm.c:497
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 parent_l1ss_cap</code>
</li>
<li>
<b>Param added. </b>
<code>u32 child_l1ss_cap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aspm_register_info *upreg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aspm_register_info *dwreg</code>
</li>
</ul>
</details>
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
</ul>
