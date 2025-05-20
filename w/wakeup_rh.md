# Function: <code>wakeup_rh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81649c30)
Location: drivers/usb/host/uhci-hcd.c:398
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81649c30-ffffffff81649d7f: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa6b0)
Location: drivers/usb/host/uhci-hcd.c:398
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff816aa6b0-ffffffff816aa807: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d87f0)
Location: drivers/usb/host/uhci-hcd.c:398
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff816d87f0-ffffffff816d8947: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816eccc0)
Location: drivers/usb/host/uhci-hcd.c:409
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff816eccc0-ffffffff816ece21: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817594b0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817594b0-ffffffff81759611: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81799580)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81799580-ffffffff817996e1: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bfef0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817bfef0-ffffffff817c0051: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817ffb30-ffffffff817ffc71: wakeup_rh (STB_LOCAL)
ffffffff818001d6-ffffffff818001f4: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81830990-ffffffff81830ad1: wakeup_rh (STB_LOCAL)
ffffffff81830f6e-ffffffff81830f8c: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81901520-ffffffff81901661: wakeup_rh (STB_LOCAL)
ffffffff8190323d-ffffffff8190325b: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81909df0-ffffffff81909f31: wakeup_rh (STB_LOCAL)
ffffffff81c20858-ffffffff81c20876: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff818eec00-ffffffff818eed3d: wakeup_rh (STB_LOCAL)
ffffffff81c12994-ffffffff81c129b1: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff8198b460-ffffffff8198b59a: wakeup_rh (STB_LOCAL)
ffffffff81d1f56f-ffffffff81d1f58c: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81ae4780-ffffffff81ae48be: wakeup_rh (STB_LOCAL)
ffffffff81eeae9b-ffffffff81eeaeb6: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70300)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81c70300-ffffffff81c70454: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd78f0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81cd78f0-ffffffff81cd7a44: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8c900)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81d8c900-ffffffff81d8ca54: wakeup_rh (STB_LOCAL)
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
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a6b910)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffff800010a6b910-ffff800010a6ba8c: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b40190)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
c0b40190-c0b40420: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3f7e0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
c000000000b3f7e0-c000000000b3fb58: wakeup_rh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000685b04)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffe000685b04-ffffffe000685cda: wakeup_rh (STB_LOCAL)
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
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff817e8d70-ffffffff817e8eb1: wakeup_rh (STB_LOCAL)
ffffffff817e934e-ffffffff817e936c: wakeup_rh.cold (STB_LOCAL)
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
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff81825810-ffffffff81825951: wakeup_rh (STB_LOCAL)
ffffffff81825dee-ffffffff81825e0c: wakeup_rh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void wakeup_rh(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-hcd.c:410
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
**Symbols:**

```
ffffffff8183a4f0-ffffffff8183a628: wakeup_rh (STB_LOCAL)
ffffffff8183fafe-ffffffff8183fb1c: wakeup_rh.cold (STB_LOCAL)
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
