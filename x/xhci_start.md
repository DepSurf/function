# Function: <code>xhci_start</code>

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
In drivers/usb/host/xhci.c (ffffffff8164d34e)
Location: drivers/usb/host/xhci.c:127
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff816adc73)
Location: drivers/usb/host/xhci.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff816dbd6c)
Location: drivers/usb/host/xhci.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f0160)
Location: drivers/usb/host/xhci.c:128
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff816f0160-ffffffff816f0204: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175c320)
Location: drivers/usb/host/xhci.c:118
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8175c320-ffffffff8175c3c4: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179cd00)
Location: drivers/usb/host/xhci.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8179cd00-ffffffff8179cda4: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c30e0)
Location: drivers/usb/host/xhci.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c30e0-ffffffff817c3184: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81807cfd-ffffffff81807d1f: xhci_start.cold (STB_LOCAL)
ffffffff81802d90-ffffffff81802e04: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81838bac-ffffffff81838bce: xhci_start.cold (STB_LOCAL)
ffffffff81833c90-ffffffff81833d04: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff8190b497-ffffffff8190b4b9: xhci_start.cold (STB_LOCAL)
ffffffff81906b60-ffffffff81906bd4: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c20ec4-ffffffff81c20ee6: xhci_start.cold (STB_LOCAL)
ffffffff8190f300-ffffffff8190f374: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:130
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c12f09-ffffffff81c12f2b: xhci_start.cold (STB_LOCAL)
ffffffff818f28d0-ffffffff818f2944: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:130
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d1fc8b-ffffffff81d1fcad: xhci_start.cold (STB_LOCAL)
ffffffff8198fb40-ffffffff8198fbb4: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81eeb84c-ffffffff81eeb86e: xhci_start.cold (STB_LOCAL)
ffffffff81aec0b0-ffffffff81aec130: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c78890)
Location: drivers/usb/host/xhci.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c78890-ffffffff81c78950: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdf910)
Location: drivers/usb/host/xhci.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81cdf910-ffffffff81cdf9d0: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d949d0)
Location: drivers/usb/host/xhci.c:157
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d949d0-ffffffff81d94a93: xhci_start (STB_GLOBAL)
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
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a710d0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffff800010a710d0-ffff800010a71180: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44edc)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c0b44edc-c0b44f78: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b45e00)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c000000000b45e00-c000000000b45f18: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000689742)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffe000689742-ffffffe000689810: xhci_start (STB_GLOBAL)
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
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817f0f5c-ffffffff817f0f7e: xhci_start.cold (STB_LOCAL)
ffffffff817ec060-ffffffff817ec0d4: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817b60f2-ffffffff817b6114: xhci_start.cold (STB_LOCAL)
ffffffff817b1170-ffffffff817b11e4: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8182da2c-ffffffff8182da4e: xhci_start.cold (STB_LOCAL)
ffffffff81828b10-ffffffff81828b84: xhci_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:131
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81847b15-ffffffff81847b37: xhci_start.cold (STB_LOCAL)
ffffffff81842ad0-ffffffff81842b44: xhci_start (STB_GLOBAL)
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
