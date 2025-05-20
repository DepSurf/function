# Function: <code>pciehp_handle_presence_or_link_change</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81550b10)
Location: drivers/pci/hotplug/pciehp_ctrl.c:216
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81550b10-ffffffff81550f0e: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:222
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81580d58-ffffffff8158104f: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff815808f0-ffffffff81580a33: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815a299b-ffffffff815a2b5d: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff815a23c0-ffffffff815a2656: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8164b634-ffffffff8164b6dc: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff8164b0a0-ffffffff8164b196: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:225
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81bfbf8a-ffffffff81bfc032: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff8166f830-ffffffff8166f926: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:225
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81bede02-ffffffff81bedeaa: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff81651d30-ffffffff81651e26: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:225
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81ce8bdd-ffffffff81ce8c85: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff816c3ab0-ffffffff816c3ba6: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:225
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81eafc87-ffffffff81eafd2f: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff817e9560-ffffffff817e9671: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f370)
Location: drivers/pci/hotplug/pciehp_ctrl.c:225
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8190f370-ffffffff8190f538: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952a20)
Location: drivers/pci/hotplug/pciehp_ctrl.c:226
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81952a20-ffffffff81952c35: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199beb0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:226
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8199beb0-ffffffff8199c0c5: pciehp_handle_presence_or_link_change (STB_GLOBAL)
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
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070ade8)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffff80001070ade8-ffff80001070b1cc: pciehp_handle_presence_or_link_change (STB_GLOBAL)
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
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7afe)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffe0004d7afe-ffffffe0004d7eac: pciehp_handle_presence_or_link_change (STB_GLOBAL)
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
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815961ab-ffffffff8159636d: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff81595bd0-ffffffff81595e66: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8158533b-ffffffff815854fd: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff81584d60-ffffffff81584ff6: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815966eb-ffffffff815968ad: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff81596110-ffffffff815963a6: pciehp_handle_presence_or_link_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller *ctrl, u32 events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:227
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815b0b66-ffffffff815b0d28: pciehp_handle_presence_or_link_change.cold (STB_LOCAL)
ffffffff815b0590-ffffffff815b0826: pciehp_handle_presence_or_link_change (STB_GLOBAL)
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
