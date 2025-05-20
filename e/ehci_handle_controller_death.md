# Function: <code>ehci_handle_controller_death</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8163a270)
Location: drivers/usb/host/ehci-timer.c:196
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8163a270-ffffffff8163a32b: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169af50)
Location: drivers/usb/host/ehci-timer.c:197
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8169af50-ffffffff8169b00b: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c9030)
Location: drivers/usb/host/ehci-timer.c:196
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff816c9030-ffffffff816c90eb: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816dda10)
Location: drivers/usb/host/ehci-timer.c:196
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff816dda10-ffffffff816ddacb: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8174a150)
Location: drivers/usb/host/ehci-timer.c:187
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8174a150-ffffffff8174a20b: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8178a100)
Location: drivers/usb/host/ehci-timer.c:187
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8178a100-ffffffff8178a1bb: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817add50)
Location: drivers/usb/host/ehci-timer.c:187
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817add50-ffffffff817ade0b: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ed00d)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817ecff0-ffffffff817ed0a0: ehci_handle_controller_death (STB_LOCAL)
ffffffff817f2b1d-ffffffff817f2b35: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181dedd)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8181dec0-ffffffff8181df70: ehci_handle_controller_death (STB_LOCAL)
ffffffff81823957-ffffffff8182396f: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f335d)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818f3340-ffffffff818f341c: ehci_handle_controller_death (STB_LOCAL)
ffffffff818f55b5-ffffffff818f55cd: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fc27d)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818fc260-ffffffff818fc33c: ehci_handle_controller_death (STB_LOCAL)
ffffffff81c202b6-ffffffff81c202ce: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818e0880)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818e0860-ffffffff818e0942: ehci_handle_controller_death (STB_LOCAL)
ffffffff81c12320-ffffffff81c12338: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8197c890)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8197c870-ffffffff8197c952: ehci_handle_controller_death (STB_LOCAL)
ffffffff81d1ed0b-ffffffff81d1ed23: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad84bf)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81ad84a0-ffffffff81ad8589: ehci_handle_controller_death (STB_LOCAL)
ffffffff81eea825-ffffffff81eea83d: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c632d0)
Location: drivers/usb/host/ehci-timer.c:187
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81c632d0-ffffffff81c633c5: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cca6d0)
Location: drivers/usb/host/ehci-timer.c:187
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81cca6d0-ffffffff81cca7c5: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7f5a0)
Location: drivers/usb/host/ehci-timer.c:187
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81d7f5a0-ffffffff81d7f68a: ehci_handle_controller_death (STB_LOCAL)
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
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a57ef8)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffff800010a57ef8-ffff800010a57fdc: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2ab24)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
c0b2ab24-c0b2abf4: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b25d00)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
c000000000b25d00-c000000000b25e70: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe0006750f2)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffe0006750f2-ffffffe0006751f6: ehci_handle_controller_death (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d62bd)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817d62a0-ffffffff817d6350: ehci_handle_controller_death (STB_LOCAL)
ffffffff817dbd37-ffffffff817dbd4f: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81812d5d)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81812d40-ffffffff81812df0: ehci_handle_controller_death (STB_LOCAL)
ffffffff818187d7-ffffffff818187ef: ehci_handle_controller_death.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_handle_controller_death(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182d82d)
Location: drivers/usb/host/ehci-timer.c:187
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8182d810-ffffffff8182d8c0: ehci_handle_controller_death (STB_LOCAL)
ffffffff818327c7-ffffffff818327df: ehci_handle_controller_death.cold (STB_LOCAL)
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
