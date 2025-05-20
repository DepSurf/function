# Function: <code>pci_pme_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435500)
Location: drivers/pci/pci.c:1768
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81435500-ffffffff814356b6: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480e70)
Location: drivers/pci/pci.c:1789
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81480e70-ffffffff81481013: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2530)
Location: drivers/pci/pci.c:1814
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff814a2530-ffffffff814a26d3: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac2b0)
Location: drivers/pci/pci.c:1834
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff814ac2b0-ffffffff814ac465: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb380)
Location: drivers/pci/pci.c:1837
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff814eb380-ffffffff814eb535: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151a940)
Location: drivers/pci/pci.c:1901
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff8151a940-ffffffff8151aaea: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815306a0)
Location: drivers/pci/pci.c:2074
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff815306a0-ffffffff8153083f: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2154
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81564a2b-ffffffff81564a43: pci_pme_active.cold (STB_LOCAL)
ffffffff81560040-ffffffff815601be: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81585d46-ffffffff81585d5e: pci_pme_active.cold (STB_LOCAL)
ffffffff81581170-ffffffff815812ee: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2220
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff8162cac3-ffffffff8162cadb: pci_pme_active.cold (STB_LOCAL)
ffffffff81625bc0-ffffffff81625d31: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2364
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81bf7c7d-ffffffff81bf7c95: pci_pme_active.cold (STB_LOCAL)
ffffffff8164b9e0-ffffffff8164bb51: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2394
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81be9b24-ffffffff81be9b3c: pci_pme_active.cold (STB_LOCAL)
ffffffff8162e5b0-ffffffff8162e721: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2425
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81ce44b1-ffffffff81ce44c9: pci_pme_active.cold (STB_LOCAL)
ffffffff8169da70-ffffffff8169dbde: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2487
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff81eaae40-ffffffff81eaae58: pci_pme_active.cold (STB_LOCAL)
ffffffff817bf620-ffffffff817bf7ae: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dbc00)
Location: drivers/pci/pci.c:2461
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff818dbc00-ffffffff818dbda6: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191ecd0)
Location: drivers/pci/pci.c:2499
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff8191ecd0-ffffffff8191ee76: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81966de0)
Location: drivers/pci/pci.c:2612
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff81966de0-ffffffff81966fb5: pci_pme_active (STB_GLOBAL)
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
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e40c8)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffff8000106e40c8-ffff8000106e4264: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087fefc)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
c087fefc-c08800cc: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085e470)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
c00000000085e470-c00000000085e6cc: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb454)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffe0004bb454-ffffffe0004bb62e: pci_pme_active (STB_GLOBAL)
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
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff8157a266-ffffffff8157a27e: pci_pme_active.cold (STB_LOCAL)
ffffffff81575690-ffffffff8157580e: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff815689a6-ffffffff815689be: pci_pme_active.cold (STB_LOCAL)
ffffffff81563df0-ffffffff81563f6e: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81579a96-ffffffff81579aae: pci_pme_active.cold (STB_LOCAL)
ffffffff81574ec0-ffffffff8157503e: pci_pme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_pme_active(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2150
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/pci.c:pci_pm_init
```
**Symbols:**

```
ffffffff81593f46-ffffffff81593f5e: pci_pme_active.cold (STB_LOCAL)
ffffffff8158f490-ffffffff8158f60e: pci_pme_active (STB_GLOBAL)
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
