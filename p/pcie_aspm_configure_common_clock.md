# Function: <code>pcie_aspm_configure_common_clock</code>

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
In drivers/pci/pcie/aspm.c (ffffffff81447f45)
Location: drivers/pci/pcie/aspm.c:180
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff814940f7)
Location: drivers/pci/pcie/aspm.c:180
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff814b5b2f)
Location: drivers/pci/pcie/aspm.c:180
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff814c0412)
Location: drivers/pci/pcie/aspm.c:218
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
In drivers/pci/pcie/aspm.c (ffffffff8150079a)
Location: drivers/pci/pcie/aspm.c:207
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
In drivers/pci/pcie/aspm.c (ffffffff815322f2)
Location: drivers/pci/pcie/aspm.c:206
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
In drivers/pci/pcie/aspm.c (ffffffff8154972d)
Location: drivers/pci/pcie/aspm.c:204
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:234
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81579530-ffffffff815797e2: pcie_aspm_configure_common_clock (STB_LOCAL)
ffffffff8157a368-ffffffff8157a3d8: pcie_aspm_configure_common_clock.cold (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffffffff8159ad8c)
Location: drivers/pci/pcie/aspm.c:238
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
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
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:238
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81639c90-ffffffff81639e8e: pcie_aspm_configure_common_clock.isra.0 (STB_LOCAL)
ffffffff8163b7c9-ffffffff8163b834: pcie_aspm_configure_common_clock.isra.0.cold (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:230
Inline: True
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81660b40-ffffffff81660d3e: pcie_aspm_configure_common_clock.isra.0 (STB_LOCAL)
ffffffff81bf8f8d-ffffffff81bf8ff8: pcie_aspm_configure_common_clock.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:230
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff81642e50-ffffffff81643102: pcie_aspm_configure_common_clock (STB_LOCAL)
ffffffff81beadc1-ffffffff81beae31: pcie_aspm_configure_common_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:230
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff816b3ba0-ffffffff816b3e52: pcie_aspm_configure_common_clock (STB_LOCAL)
ffffffff81ce5cec-ffffffff81ce5d5c: pcie_aspm_configure_common_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:230
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff817d7140-ffffffff817d7409: pcie_aspm_configure_common_clock (STB_LOCAL)
ffffffff81eac713-ffffffff81eac781: pcie_aspm_configure_common_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff818f8660)
Location: drivers/pci/pcie/aspm.c:231
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff818f8660-ffffffff818f8983: pcie_aspm_configure_common_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8193b920)
Location: drivers/pci/pcie/aspm.c:199
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff8193b920-ffffffff8193bb73: pcie_aspm_configure_common_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_aspm_configure_common_clock(struct pcie_link_state *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff819848e0)
Location: drivers/pci/pcie/aspm.c:202
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
**Symbols:**

```
ffffffff819848e0-ffffffff81984b33: pcie_aspm_configure_common_clock (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffff8000107027ec)
Location: drivers/pci/pcie/aspm.c:238
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
In drivers/pci/pcie/aspm.c (c089a24c)
Location: drivers/pci/pcie/aspm.c:238
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
In drivers/pci/pcie/aspm.c (ffffffe0004d1250)
Location: drivers/pci/pcie/aspm.c:238
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
In drivers/pci/pcie/aspm.c (ffffffff8158ec1c)
Location: drivers/pci/pcie/aspm.c:238
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
In drivers/pci/pcie/aspm.c (ffffffff8157d75c)
Location: drivers/pci/pcie/aspm.c:238
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
In drivers/pci/pcie/aspm.c (ffffffff8158eadc)
Location: drivers/pci/pcie/aspm.c:238
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
In drivers/pci/pcie/aspm.c (ffffffff815a8f8c)
Location: drivers/pci/pcie/aspm.c:238
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
