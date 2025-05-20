# Function: <code>pci_enable_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814357d5)
Location: include/linux/pci.h:1093
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_back_from_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff814397a4)
Location: include/linux/pci.h:1093
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814822f6)
Location: include/linux/pci.h:1087
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff81485654)
Location: include/linux/pci.h:1087
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3886)
Location: include/linux/pci.h:1117
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff814a6e14)
Location: include/linux/pci.h:1117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac570)
Location: drivers/pci/pci.c:1911
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
ffffffff814ac570-ffffffff814ac62d: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb640)
Location: drivers/pci/pci.c:1914
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff814eb640-ffffffff814eb716: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b0e0)
Location: drivers/pci/pci.c:2029
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff8151b0e0-ffffffff8151b110: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530e60)
Location: drivers/pci/pci.c:2205
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff81530e60-ffffffff81530e90: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815607a0)
Location: drivers/pci/pci.c:2285
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff815607a0-ffffffff815607d0: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815818c0)
Location: drivers/pci/pci.c:2281
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff815818c0-ffffffff815818f0: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81629ef7)
Location: drivers/pci/pci.c:2351
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff81626550-ffffffff81626580: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8165033a)
Location: drivers/pci/pci.c:2495
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff8164c260-ffffffff8164c290: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81632ef8)
Location: drivers/pci/pci.c:2525
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff8162ee40-ffffffff8162ee70: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3067)
Location: drivers/pci/pci.c:2563
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff8169e750-ffffffff8169e780: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5246)
Location: drivers/pci/pci.c:2625
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff817c0730-ffffffff817c0774: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e22e4)
Location: drivers/pci/pci.c:2599
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff818dcf60-ffffffff818dcfa4: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925724)
Location: drivers/pci/pci.c:2637
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff81920310-ffffffff81920354: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196dea6)
Location: drivers/pci/pci.c:2750
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff819684a0-ffffffff819684e4: pci_enable_wake (STB_GLOBAL)
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
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7194)
Location: drivers/pci/pci.c:2281
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffff8000106e49c0-ffff8000106e4a1c: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08823a8)
Location: drivers/pci/pci.c:2281
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
c088070c-c0880750: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861840)
Location: drivers/pci/pci.c:2281
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
c00000000085f1d0-c00000000085f218: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd9ee)
Location: drivers/pci/pci.c:2281
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
```
**Symbols:**

```
ffffffe0004bbde6-ffffffe0004bbe36: pci_enable_wake (STB_GLOBAL)
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
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575de0)
Location: drivers/pci/pci.c:2281
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
```
**Symbols:**

```
ffffffff81575de0-ffffffff81575e10: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564540)
Location: drivers/pci/pci.c:2281
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff81564540-ffffffff81564570: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575610)
Location: drivers/pci/pci.c:2281
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff81575610-ffffffff81575640: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev *pci_dev, pci_power_t state, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fbe0)
Location: drivers/pci/pci.c:2281
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
```
**Symbols:**

```
ffffffff8158fbe0-ffffffff8158fc10: pci_enable_wake (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *pci_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_dev *dev</code>
</li>
</ul>
</details>
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
