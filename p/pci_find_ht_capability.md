# Function: <code>pci_find_ht_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435340)
Location: drivers/pci/pci.c:406
Inline: False
Direct callers:
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/htirq.c:__ht_create_irq
```
**Symbols:**

```
ffffffff81435340-ffffffff81435378: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480ca0)
Location: drivers/pci/pci.c:427
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/htirq.c:__ht_create_irq
```
**Symbols:**

```
ffffffff81480ca0-ffffffff81480cd8: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2360)
Location: drivers/pci/pci.c:427
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/htirq.c:__ht_create_irq
```
**Symbols:**

```
ffffffff814a2360-ffffffff814a2398: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac100)
Location: drivers/pci/pci.c:429
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/htirq.c:__ht_create_irq
```
**Symbols:**

```
ffffffff814ac100-ffffffff814ac138: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb1d0)
Location: drivers/pci/pci.c:430
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff814eb1d0-ffffffff814eb208: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151a790)
Location: drivers/pci/pci.c:442
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff8151a790-ffffffff8151a7cd: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815304f0)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff815304f0-ffffffff8153052d: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155fcd0)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff8155fcd0-ffffffff8155fd10: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580e00)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81580e00-ffffffff81580e40: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626a70)
Location: drivers/pci/pci.c:674
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81626a70-ffffffff81626b05: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164c6e0)
Location: drivers/pci/pci.c:683
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff8164c6e0-ffffffff8164c775: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162f260)
Location: drivers/pci/pci.c:683
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff8162f260-ffffffff8162f2f5: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169ed70)
Location: drivers/pci/pci.c:693
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff8169ed70-ffffffff8169ee05: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c1020)
Location: drivers/pci/pci.c:710
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff817c1020-ffffffff817c10ca: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dd700)
Location: drivers/pci/pci.c:694
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff818dd700-ffffffff818dd7aa: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81920bb0)
Location: drivers/pci/pci.c:709
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81920bb0-ffffffff81920c4f: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81968d50)
Location: drivers/pci/pci.c:709
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81968d50-ffffffff81968def: pci_find_ht_capability (STB_GLOBAL)
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
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3c58)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffff8000106e3c58-ffff8000106e3cb0: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087fb14)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
c087fb14-c087fb5c: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ded0)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
c00000000085ded0-c00000000085df50: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb0d2)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffe0004bb0d2-ffffffe0004bb124: pci_find_ht_capability (STB_GLOBAL)
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
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575320)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81575320-ffffffff81575360: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563a80)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81563a80-ffffffff81563ac0: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574b50)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff81574b50-ffffffff81574b90: pci_find_ht_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_find_ht_capability(struct pci_dev *dev, int ht_cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f120)
Location: drivers/pci/pci.c:608
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
```
**Symbols:**

```
ffffffff8158f120-ffffffff8158f160: pci_find_ht_capability (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u8</code>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
