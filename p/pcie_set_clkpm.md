# Function: <code>pcie_set_clkpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814474b0)
Location: drivers/pci/pcie/aspm.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
```
**Symbols:**

```
ffffffff814474b0-ffffffff814474d8: pcie_set_clkpm (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffffffff814939b9)
Location: drivers/pci/pcie/aspm.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
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
In drivers/pci/pcie/aspm.c (ffffffff814b5349)
Location: drivers/pci/pcie/aspm.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
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
In drivers/pci/pcie/aspm.c (ffffffff814bf947)
Location: drivers/pci/pcie/aspm.c:177
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
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
In drivers/pci/pcie/aspm.c (ffffffff814ffcc7)
Location: drivers/pci/pcie/aspm.c:166
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
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
In drivers/pci/pcie/aspm.c (ffffffff815318a1)
Location: drivers/pci/pcie/aspm.c:165
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
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
In drivers/pci/pcie/aspm.c (ffffffff81548f7f)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
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
In drivers/pci/pcie/aspm.c (ffffffff815790f8)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8159aa99)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816397e0)
Location: drivers/pci/pcie/aspm.c:163
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
ffffffff816397e0-ffffffff81639890: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81660690)
Location: drivers/pci/pcie/aspm.c:155
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
ffffffff81660690-ffffffff81660740: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81642b70)
Location: drivers/pci/pcie/aspm.c:155
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
ffffffff81642b70-ffffffff81642c14: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816b3850)
Location: drivers/pci/pcie/aspm.c:155
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
ffffffff816b3850-ffffffff816b38f4: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff817d6fa0)
Location: drivers/pci/pcie/aspm.c:155
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
ffffffff817d6fa0-ffffffff817d704c: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff818f84d0)
Location: drivers/pci/pcie/aspm.c:156
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
ffffffff818f84d0-ffffffff818f857c: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8193bb90)
Location: drivers/pci/pcie/aspm.c:154
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff8193bb90-ffffffff8193bc4a: pcie_set_clkpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state *link, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81984b50)
Location: drivers/pci/pcie/aspm.c:157
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
**Symbols:**

```
ffffffff81984b50-ffffffff81984c0a: pcie_set_clkpm (STB_LOCAL)
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
In drivers/pci/pcie/aspm.c (ffff80001070243c)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (c0899f00)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffe0004d10c0)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8158e929)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8157d469)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff8158e7e9)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/pcie/aspm.c (ffffffff815a8c99)
Location: drivers/pci/pcie/aspm.c:163
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
