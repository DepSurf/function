# Function: <code>check_dev_quirk</code>

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
In arch/x86/kernel/early-quirks.c (ffffffff81f6f3f6)
Location: arch/x86/kernel/early-quirks.c:654
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_quirks
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
In arch/x86/kernel/early-quirks.c (ffffffff81f97205)
Location: arch/x86/kernel/early-quirks.c:706
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff81fd26e6)
Location: arch/x86/kernel/early-quirks.c:698
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff820b3331)
Location: arch/x86/kernel/early-quirks.c:699
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff826b9b74)
Location: arch/x86/kernel/early-quirks.c:702
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff826e3900)
Location: arch/x86/kernel/early-quirks.c:728
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff8289a274)
Location: arch/x86/kernel/early-quirks.c:760
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff828b1fc4)
Location: arch/x86/kernel/early-quirks.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff828b5413)
Location: arch/x86/kernel/early-quirks.c:769
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff82cda542)
Location: arch/x86/kernel/early-quirks.c:769
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
```
**Symbols:**

```
ffffffff82cda542-ffffffff82cda678: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff82fc6996)
Location: arch/x86/kernel/early-quirks.c:770
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
```
**Symbols:**

```
ffffffff82fc6996-ffffffff82fc6acc: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff831d124e)
Location: arch/x86/kernel/early-quirks.c:772
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
```
**Symbols:**

```
ffffffff831d124e-ffffffff831d1384: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff832b37b8)
Location: arch/x86/kernel/early-quirks.c:775
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
```
**Symbols:**

```
ffffffff832b37b8-ffffffff832b3a67: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff83464edc)
Location: arch/x86/kernel/early-quirks.c:779
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
```
**Symbols:**

```
ffffffff83464edc-ffffffff83465199: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff83e880e0)
Location: arch/x86/kernel/early-quirks.c:779
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
```
**Symbols:**

```
ffffffff83e880e0-ffffffff83e885b9: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff836ab680)
Location: arch/x86/kernel/early-quirks.c:779
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
```
**Symbols:**

```
ffffffff836ab680-ffffffff836abb58: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_dev_quirk(int num, int slot, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff838dbe10)
Location: arch/x86/kernel/early-quirks.c:779
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
```
**Symbols:**

```
ffffffff838dbe10-ffffffff838dc2e8: check_dev_quirk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/early-quirks.c (ffffffff828a341f)
Location: arch/x86/kernel/early-quirks.c:769
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff8289b561)
Location: arch/x86/kernel/early-quirks.c:769
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff828b632f)
Location: arch/x86/kernel/early-quirks.c:769
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
In arch/x86/kernel/early-quirks.c (ffffffff828b6416)
Location: arch/x86/kernel/early-quirks.c:769
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
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
