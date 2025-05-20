# Function: <code>pciehp_handle_button_press</code>

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
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81550950)
Location: drivers/pci/hotplug/pciehp_ctrl.c:153
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81550950-ffffffff81550aab: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:159
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81580c4d-ffffffff81580d58: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff81580800-ffffffff81580882: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815a2886-ffffffff815a299b: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff815a22d0-ffffffff815a2352: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8164b51f-ffffffff8164b634: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff8164afb0-ffffffff8164b032: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81bfbe75-ffffffff81bfbf8a: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff8166f740-ffffffff8166f7c2: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81bedced-ffffffff81bede02: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff81651c40-ffffffff81651cc2: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81ce8ac8-ffffffff81ce8bdd: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff816c39c0-ffffffff816c3a42: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81eafb64-ffffffff81eafc87: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff817e9460-ffffffff817e94e2: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f120)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8190f120-ffffffff8190f2df: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff819527b0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff819527b0-ffffffff81952984: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199bc40)
Location: drivers/pci/hotplug/pciehp_ctrl.c:161
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8199bc40-ffffffff8199be14: pciehp_handle_button_press (STB_GLOBAL)
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
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070abe8)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffff80001070abe8-ffff80001070ad78: pciehp_handle_button_press (STB_GLOBAL)
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
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d791c)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffe0004d791c-ffffffe0004d7a92: pciehp_handle_button_press (STB_GLOBAL)
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
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81596096-ffffffff815961ab: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff81595ae0-ffffffff81595b62: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81585226-ffffffff8158533b: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff81584c70-ffffffff81584cf2: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815965d6-ffffffff815966eb: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff81596020-ffffffff815960a2: pciehp_handle_button_press (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pciehp_handle_button_press(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:163
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815b0a51-ffffffff815b0b66: pciehp_handle_button_press.cold (STB_LOCAL)
ffffffff815b04a0-ffffffff815b0522: pciehp_handle_button_press (STB_GLOBAL)
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
