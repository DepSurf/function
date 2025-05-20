# Function: <code>pciehp_card_present</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815520c9)
Location: drivers/pci/hotplug/pciehp_hpc.c:374
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81552040-ffffffff81552092: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158201a)
Location: drivers/pci/hotplug/pciehp_hpc.c:376
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81581f90-ffffffff81581fe2: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3a20)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffffffff815a3a20-ffffffff815a3a86: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c600)
Location: drivers/pci/hotplug/pciehp_hpc.c:436
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8164c600-ffffffff8164c664: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670950)
Location: drivers/pci/hotplug/pciehp_hpc.c:439
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81670950-ffffffff816709b4: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652e10)
Location: drivers/pci/hotplug/pciehp_hpc.c:439
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81652e10-ffffffff81652e74: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4b80)
Location: drivers/pci/hotplug/pciehp_hpc.c:439
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff816c4b80-ffffffff816c4be4: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea820)
Location: drivers/pci/hotplug/pciehp_hpc.c:441
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff817ea820-ffffffff817ea894: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910a00)
Location: drivers/pci/hotplug/pciehp_hpc.c:441
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81910a00-ffffffff81910a74: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954120)
Location: drivers/pci/hotplug/pciehp_hpc.c:435
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81954120-ffffffff81954194: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d5b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:436
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8199d5b0-ffffffff8199d624: pciehp_card_present (STB_GLOBAL)
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
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c530)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffff80001070c530-ffff80001070c5b4: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8e5e)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffffffe0004d8e5e-ffffffe0004d8eae: pciehp_card_present (STB_GLOBAL)
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
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597230)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffffffff81597230-ffffffff81597296: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815863c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffffffff815863c0-ffffffff81586426: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597770)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffffffff81597770-ffffffff815977d6: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pciehp_card_present(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1bb0)
Location: drivers/pci/hotplug/pciehp_hpc.c:400
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
```
**Symbols:**

```
ffffffff815b1bb0-ffffffff815b1c16: pciehp_card_present (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
