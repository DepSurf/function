# Function: <code>pcie_set_clkpm_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81447430)
Location: drivers/pci/pcie/aspm.c:126
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
**Symbols:**

```
ffffffff81447430-ffffffff814474a9: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814935f0)
Location: drivers/pci/pcie/aspm.c:126
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff814935f0-ffffffff81493665: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814b4f80)
Location: drivers/pci/pcie/aspm.c:126
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff814b4f80-ffffffff814b4ff5: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814bf430)
Location: drivers/pci/pcie/aspm.c:164
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff814bf430-ffffffff814bf4a6: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814ff7b0)
Location: drivers/pci/pcie/aspm.c:153
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff814ff7b0-ffffffff814ff826: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81531370)
Location: drivers/pci/pcie/aspm.c:152
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81531370-ffffffff815313e6: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81548810)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81548810-ffffffff81548885: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81578950)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81578950-ffffffff815789c6: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8159a160)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8159a160-ffffffff8159a1d6: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81639810)
Location: drivers/pci/pcie/aspm.c:150
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816606c0)
Location: drivers/pci/pcie/aspm.c:142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
In drivers/pci/pcie/aspm.c (ffffffff81642ba0)
Location: drivers/pci/pcie/aspm.c:142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
In drivers/pci/pcie/aspm.c (ffffffff816b3880)
Location: drivers/pci/pcie/aspm.c:142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
In drivers/pci/pcie/aspm.c (ffffffff817d6fd0)
Location: drivers/pci/pcie/aspm.c:142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
In drivers/pci/pcie/aspm.c (ffffffff818f8500)
Location: drivers/pci/pcie/aspm.c:143
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
In drivers/pci/pcie/aspm.c (ffffffff8193bbc0)
Location: drivers/pci/pcie/aspm.c:141
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
In drivers/pci/pcie/aspm.c (ffffffff81984b80)
Location: drivers/pci/pcie/aspm.c:144
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
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
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010701a98)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffff800010701a98-ffff800010701b20: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c08996a0)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
c08996a0-c089970c: pcie_set_clkpm_nocheck (STB_LOCAL)
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
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d0800)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffe0004d0800-ffffffe0004d0884: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158dff0)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8158dff0-ffffffff8158e066: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157cb30)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8157cb30-ffffffff8157cba6: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158deb0)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8158deb0-ffffffff8158df26: pcie_set_clkpm_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815a8360)
Location: drivers/pci/pcie/aspm.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff815a8360-ffffffff815a83d6: pcie_set_clkpm_nocheck (STB_LOCAL)
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
