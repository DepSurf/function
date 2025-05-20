# Function: <code>pcie_config_aspm_l1ss</code>

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
In drivers/pci/pcie/aspm.c (ffffffff814bf64f)
Location: drivers/pci/pcie/aspm.c:609
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff814ff9cf)
Location: drivers/pci/pcie/aspm.c:634
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff815315aa)
Location: drivers/pci/pcie/aspm.c:659
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff81548a4a)
Location: drivers/pci/pcie/aspm.c:657
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff81578b90)
Location: drivers/pci/pcie/aspm.c:672
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff8159a3a0)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcie_config_aspm_l1ss(struct pcie_link_state *link, u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8163a540)
Location: drivers/pci/pcie/aspm.c:667
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff8163a540-ffffffff8163a7b6: pcie_config_aspm_l1ss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcie_config_aspm_l1ss(struct pcie_link_state *link, u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81660e20)
Location: drivers/pci/pcie/aspm.c:685
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
**Symbols:**

```
ffffffff81660e20-ffffffff81660fa9: pcie_config_aspm_l1ss (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffffffff816437bd)
Location: drivers/pci/pcie/aspm.c:685
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816b454d)
Location: drivers/pci/pcie/aspm.c:685
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff817d7c3d)
Location: drivers/pci/pcie/aspm.c:677
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff818f927d)
Location: drivers/pci/pcie/aspm.c:702
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff8193c632)
Location: drivers/pci/pcie/aspm.c:663
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff81984e90)
Location: drivers/pci/pcie/aspm.c:664
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
```
</details>
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
In drivers/pci/pcie/aspm.c (ffff800010701cc8)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (c08998d8)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffe0004d0a10)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff8158e230)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff8157cd70)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff8158e0f0)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
In drivers/pci/pcie/aspm.c (ffffffff815a85a0)
Location: drivers/pci/pcie/aspm.c:676
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
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
</ul>
