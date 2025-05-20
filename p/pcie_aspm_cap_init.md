# Function: <code>pcie_aspm_cap_init</code>

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
In drivers/pci/pcie/aspm.c (ffffffff81447df6)
Location: drivers/pci/pcie/aspm.c:341
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
In drivers/pci/pcie/aspm.c (ffffffff81493f8a)
Location: drivers/pci/pcie/aspm.c:341
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
In drivers/pci/pcie/aspm.c (ffffffff814b5914)
Location: drivers/pci/pcie/aspm.c:341
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
In drivers/pci/pcie/aspm.c (ffffffff814c01dc)
Location: drivers/pci/pcie/aspm.c:479
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
In drivers/pci/pcie/aspm.c (ffffffff8150055b)
Location: drivers/pci/pcie/aspm.c:504
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
In drivers/pci/pcie/aspm.c (ffffffff81532151)
Location: drivers/pci/pcie/aspm.c:529
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
In drivers/pci/pcie/aspm.c (ffffffff8154958c)
Location: drivers/pci/pcie/aspm.c:527
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815797f0)
Location: drivers/pci/pcie/aspm.c:542
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff815797f0-ffffffff81579c87: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8159acf0-ffffffff8159b459: pcie_aspm_cap_init (STB_LOCAL)
ffffffff8159bd88-ffffffff8159be14: pcie_aspm_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8163a1e0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8163a1e0-ffffffff8163a53d: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81661e70)
Location: drivers/pci/pcie/aspm.c:543
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81661e70-ffffffff8166226b: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81644220)
Location: drivers/pci/pcie/aspm.c:543
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81644220-ffffffff8164461b: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816b4fc0)
Location: drivers/pci/pcie/aspm.c:543
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff816b4fc0-ffffffff816b53be: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff817d88b0)
Location: drivers/pci/pcie/aspm.c:551
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff817d88b0-ffffffff817d8bf4: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff818fa2e0)
Location: drivers/pci/pcie/aspm.c:623
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff818fa2e0-ffffffff818fa4a2: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8193d7f0)
Location: drivers/pci/pcie/aspm.c:584
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8193d7f0-ffffffff8193d9b2: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff819859e0)
Location: drivers/pci/pcie/aspm.c:586
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff819859e0-ffffffff81985b90: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010702740)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffff800010702740-ffff800010702eac: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c089a1a0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
c089a1a0-c089a90c: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d11b2)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffe0004d11b2-ffffffe0004d18e2: pcie_aspm_cap_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8158eb80-ffffffff8158f2e9: pcie_aspm_cap_init (STB_LOCAL)
ffffffff8158fc18-ffffffff8158fca4: pcie_aspm_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8157d6c0-ffffffff8157de29: pcie_aspm_cap_init (STB_LOCAL)
ffffffff8157e758-ffffffff8157e7e4: pcie_aspm_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8158ea40-ffffffff8158f1a9: pcie_aspm_cap_init (STB_LOCAL)
ffffffff8158fad8-ffffffff8158fb64: pcie_aspm_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state *link, int blacklist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:546
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff815a8ef0-ffffffff815a9659: pcie_aspm_cap_init (STB_LOCAL)
ffffffff815a9f88-ffffffff815aa014: pcie_aspm_cap_init.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
