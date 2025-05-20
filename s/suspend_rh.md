# Function: <code>suspend_rh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81648210)
Location: drivers/usb/host/uhci-hcd.c:283
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81648210-ffffffff816484dd: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a8cf0)
Location: drivers/usb/host/uhci-hcd.c:283
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff816a8cf0-ffffffff816a8fc7: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d6e10)
Location: drivers/usb/host/uhci-hcd.c:283
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff816d6e10-ffffffff816d70e7: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb0e0)
Location: drivers/usb/host/uhci-hcd.c:287
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff816eb0e0-ffffffff816eb387: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817578d0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817578d0-ffffffff81757b7d: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817998e0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817998e0-ffffffff81799b8e: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bf560)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817bf560-ffffffff817bf80e: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817fee90-ffffffff817ff144: suspend_rh (STB_LOCAL)
ffffffff8180007d-ffffffff81800095: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff8182fcf0-ffffffff8182ffa4: suspend_rh (STB_LOCAL)
ffffffff81830e15-ffffffff81830e2d: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81900e00-ffffffff819010d4: suspend_rh (STB_LOCAL)
ffffffff81903225-ffffffff8190323d: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff819096d0-ffffffff819099a4: suspend_rh (STB_LOCAL)
ffffffff81c20840-ffffffff81c20858: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff818edf60-ffffffff818ee200: suspend_rh (STB_LOCAL)
ffffffff81c128aa-ffffffff81c128c2: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff8198a710-ffffffff8198a9c4: suspend_rh (STB_LOCAL)
ffffffff81d1f423-ffffffff81d1f450: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81ae5e90-ffffffff81ae6142: suspend_rh (STB_LOCAL)
ffffffff81eeafbd-ffffffff81eeafea: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81c71bf0-ffffffff81c71ebe: suspend_rh (STB_LOCAL)
ffffffff820a55b2-ffffffff820a55c7: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81cd91c0-ffffffff81cd949e: suspend_rh (STB_LOCAL)
ffffffff82126abe-ffffffff82126ad3: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81d8e1d0-ffffffff81d8e4ae: suspend_rh (STB_LOCAL)
ffffffff822082c1-ffffffff822082d6: suspend_rh.cold (STB_LOCAL)
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
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a6c3e0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffff800010a6c3e0-ffff800010a6c6e0: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3e9b8)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
c0b3e9b8-c0b3edcc: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3e7c0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
c000000000b3e7c0-c000000000b3ece4: suspend_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000685f96)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffe000685f96-ffffffe000686224: suspend_rh (STB_LOCAL)
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
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817e80d0-ffffffff817e8384: suspend_rh (STB_LOCAL)
ffffffff817e91f5-ffffffff817e920d: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81824b70-ffffffff81824e24: suspend_rh (STB_LOCAL)
ffffffff81825c95-ffffffff81825cad: suspend_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void suspend_rh(struct uhci_hcd *uhci, enum uhci_rh_state new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff8183d8a0-ffffffff8183db4b: suspend_rh (STB_LOCAL)
ffffffff8183fbb3-ffffffff8183fbcb: suspend_rh.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
