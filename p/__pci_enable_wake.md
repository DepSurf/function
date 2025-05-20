# Function: <code>__pci_enable_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool runtime, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814356c0)
Location: drivers/pci/pci.c:1845
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
```
**Symbols:**

```
ffffffff814356c0-ffffffff814357c8: __pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool runtime, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481020)
Location: drivers/pci/pci.c:1866
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
```
**Symbols:**

```
ffffffff81481020-ffffffff81481136: __pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool runtime, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a26e0)
Location: drivers/pci/pci.c:1891
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
```
**Symbols:**

```
ffffffff814a26e0-ffffffff814a27fb: __pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b010)
Location: drivers/pci/pci.c:1978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff8151b010-ffffffff8151b0dd: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530d80)
Location: drivers/pci/pci.c:2151
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff81530d80-ffffffff81530e53: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815606c0)
Location: drivers/pci/pci.c:2231
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff815606c0-ffffffff8156079b: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815817e0)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff815817e0-ffffffff815818bb: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626460)
Location: drivers/pci/pci.c:2297
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81626460-ffffffff8162654b: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164c170)
Location: drivers/pci/pci.c:2441
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8164c170-ffffffff8164c25b: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162ed50)
Location: drivers/pci/pci.c:2471
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8162ed50-ffffffff8162ee3b: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169e67e)
Location: drivers/pci/pci.c:2502
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8169e650-ffffffff8169e745: __pci_enable_wake (STB_LOCAL)
ffffffff81ce4610-ffffffff81ce4650: __pci_enable_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2564
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff817c0670-ffffffff817c072e: __pci_enable_wake (STB_LOCAL)
ffffffff81eaafbf-ffffffff81eaafff: __pci_enable_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2538
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff818dce90-ffffffff818dcf4e: __pci_enable_wake (STB_LOCAL)
ffffffff8208f00d-ffffffff8208f04d: __pci_enable_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2576
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81920240-ffffffff819202f6: __pci_enable_wake (STB_LOCAL)
ffffffff8210f387-ffffffff8210f3b7: __pci_enable_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2689
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff819683d0-ffffffff81968488: __pci_enable_wake (STB_LOCAL)
ffffffff821ed00c-ffffffff821ed03e: __pci_enable_wake.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4888)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffff8000106e4888-ffff8000106e49c0: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08805e0)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
c08805e0-c088070c: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085f020)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
c00000000085f020-c00000000085f1c4: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bbcee)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffe0004bbcee-ffffffe0004bbde6: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575d00)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff81575d00-ffffffff81575ddb: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564460)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff81564460-ffffffff8156453b: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575530)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff81575530-ffffffff8157560b: __pci_enable_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fb00)
Location: drivers/pci/pci.c:2227
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_enable_wake
```
**Symbols:**

```
ffffffff8158fb00-ffffffff8158fbdb: __pci_enable_wake (STB_LOCAL)
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
