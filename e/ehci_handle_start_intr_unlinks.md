# Function: <code>ehci_handle_start_intr_unlinks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81639750)
Location: drivers/usb/host/ehci-timer.c:220
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81639750-ffffffff816397e0: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169a410)
Location: drivers/usb/host/ehci-timer.c:221
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8169a410-ffffffff8169a4b0: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c84f0)
Location: drivers/usb/host/ehci-timer.c:220
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff816c84f0-ffffffff816c8590: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816dcf50)
Location: drivers/usb/host/ehci-timer.c:220
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff816dcf50-ffffffff816dcff0: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81749690)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81749690-ffffffff81749730: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817896e0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817896e0-ffffffff81789780: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ac230)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817ac230-ffffffff817ac2d0: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817eb440)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817eb440-ffffffff817eb4e0: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181c310)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8181c310-ffffffff8181c3b0: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f0aa0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818f0aa0-ffffffff818f0b65: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f9dc0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818f9dc0-ffffffff818f9e85: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dcbb0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818dcbb0-ffffffff818dcc75: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff819785a0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff819785a0-ffffffff81978665: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad5e50)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81ad5e50-ffffffff81ad5f23: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c60e90)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81c60e90-ffffffff81c60f63: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8250)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81cc8250-ffffffff81cc8323: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dc60)
Location: drivers/usb/host/ehci-timer.c:211
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81d7dc60-ffffffff81d7dd33: ehci_handle_start_intr_unlinks (STB_LOCAL)
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
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a55c68)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffff800010a55c68-ffff800010a55d24: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b289d4)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
c0b289d4-c0b28a94: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b228a0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
c000000000b228a0-c000000000b2297c: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000673536)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffe000673536-ffffffe0006735d4: ehci_handle_start_intr_unlinks (STB_LOCAL)
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
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d46f0)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff817d46f0-ffffffff817d4790: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81811190)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81811190-ffffffff81811230: ehci_handle_start_intr_unlinks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ehci_handle_start_intr_unlinks(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182bc60)
Location: drivers/usb/host/ehci-timer.c:211
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff8182bc60-ffffffff8182bd00: ehci_handle_start_intr_unlinks (STB_LOCAL)
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
