# Function: <code>pci_target_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814334f0)
Location: drivers/pci/pci.c:1919
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
**Symbols:**

```
ffffffff814334f0-ffffffff814335a0: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147ed60)
Location: drivers/pci/pci.c:1940
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8147ed60-ffffffff8147ee1c: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a0400)
Location: drivers/pci/pci.c:1965
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff814a0400-ffffffff814a04d9: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814abb90)
Location: drivers/pci/pci.c:1978
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff814abb90-ffffffff814abc6f: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eac50)
Location: drivers/pci/pci.c:1988
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff814eac50-ffffffff814ead3b: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151a1f0)
Location: drivers/pci/pci.c:2069
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8151a1f0-ffffffff8151a2e6: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152ff60)
Location: drivers/pci/pci.c:2245
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8152ff60-ffffffff81530057: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155f740)
Location: drivers/pci/pci.c:2325
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8155f740-ffffffff8155f837: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580880)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81580880-ffffffff81580977: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81624320)
Location: drivers/pci/pci.c:2391
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81624320-ffffffff81624417: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81649ee0)
Location: drivers/pci/pci.c:2535
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81649ee0-ffffffff81649fd7: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162ca90)
Location: drivers/pci/pci.c:2565
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8162ca90-ffffffff8162cb96: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169c600)
Location: drivers/pci/pci.c:2603
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8169c600-ffffffff8169c72e: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c0aa0)
Location: drivers/pci/pci.c:2665
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff817c0aa0-ffffffff817c0b7e: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dd360)
Location: drivers/pci/pci.c:2639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff818dd360-ffffffff818dd43e: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819208f0)
Location: drivers/pci/pci.c:2677
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff819208f0-ffffffff819209ad: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81968a80)
Location: drivers/pci/pci.c:2790
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81968a80-ffffffff81968b44: pci_target_state (STB_LOCAL)
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
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3540)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffff8000106e3540-ffff8000106e3678: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087f498)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
c087f498-c087f5dc: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085d610)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
c00000000085d610-c00000000085d80c: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004babf8)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffe0004babf8-ffffffe0004bace8: pci_target_state (STB_LOCAL)
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
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574da0)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81574da0-ffffffff81574e97: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563500)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81563500-ffffffff815635f7: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815745d0)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff815745d0-ffffffff815746c7: pci_target_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_target_state(struct pci_dev *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158eba0)
Location: drivers/pci/pci.c:2321
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff8158eba0-ffffffff8158ec97: pci_target_state (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool wakeup</code>
</li>
</ul>
</details>
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
