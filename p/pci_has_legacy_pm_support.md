# Function: <code>pci_has_legacy_pm_support</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814397c0)
Location: drivers/pci/pci-driver.c:647
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff814397c0-ffffffff81439828: pci_has_legacy_pm_support.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81485670)
Location: drivers/pci/pci-driver.c:647
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81485670-ffffffff814856d8: pci_has_legacy_pm_support.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a6e30)
Location: drivers/pci/pci-driver.c:645
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff814a6e30-ffffffff814a6e98: pci_has_legacy_pm_support.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b0e10)
Location: drivers/pci/pci-driver.c:662
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff814b0e10-ffffffff814b0e72: pci_has_legacy_pm_support.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814f0340)
Location: drivers/pci/pci-driver.c:660
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff814f0340-ffffffff814f03a2: pci_has_legacy_pm_support.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8151fae0)
Location: drivers/pci/pci-driver.c:660
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff8151fae0-ffffffff8151fb43: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81535910)
Location: drivers/pci/pci-driver.c:660
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81535910-ffffffff81535973: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815652c0)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff815652c0-ffffffff8156532e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815865d0)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff815865d0-ffffffff8158663e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162d6b0)
Location: drivers/pci/pci-driver.c:634
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff8162d6b0-ffffffff8162d742: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81652dc0)
Location: drivers/pci/pci-driver.c:639
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81652dc0-ffffffff81652e52: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81635880)
Location: drivers/pci/pci-driver.c:639
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81635880-ffffffff8163590e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a5a60)
Location: drivers/pci/pci-driver.c:652
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff816a5a60-ffffffff816a5af1: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c8400)
Location: drivers/pci/pci-driver.c:683
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff817c8400-ffffffff817c84af: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e5c80)
Location: drivers/pci/pci-driver.c:683
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff818e5c80-ffffffff818e5d2f: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff819292c0)
Location: drivers/pci/pci-driver.c:684
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff819292c0-ffffffff8192936f: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81971ac0)
Location: drivers/pci/pci-driver.c:696
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81971ac0-ffffffff81971b6f: pci_has_legacy_pm_support (STB_LOCAL)
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
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106eac50)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffff8000106eac50-ffff8000106eacdc: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0885b0c)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
c0885b0c-c0885bc4: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000865fc0)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
c000000000865fc0-c000000000866078: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157aaf0)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
```
**Symbols:**

```
ffffffff8157aaf0-ffffffff8157ab5e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81569230)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81569230-ffffffff8156929e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157a320)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff8157a320-ffffffff8157a38e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev *pci_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81594930)
Location: drivers/pci/pci-driver.c:661
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
**Symbols:**

```
ffffffff81594930-ffffffff8159499e: pci_has_legacy_pm_support (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
