# Function: <code>end_unlink_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81633300)
Location: drivers/usb/host/ehci-q.c:1301
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81633300-ffffffff8163355c: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81694010)
Location: drivers/usb/host/ehci-q.c:1319
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81694010-ffffffff816942c0: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c20f0)
Location: drivers/usb/host/ehci-q.c:1317
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff816c20f0-ffffffff816c23a0: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d64d0)
Location: drivers/usb/host/ehci-q.c:1317
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff816d64d0-ffffffff816d679c: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81742c00)
Location: drivers/usb/host/ehci-q.c:1304
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81742c00-ffffffff81742ecc: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81783710)
Location: drivers/usb/host/ehci-q.c:1300
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81783710-ffffffff817839c9: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817aa670)
Location: drivers/usb/host/ehci-q.c:1300
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff817aa670-ffffffff817aa929: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:1300
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffffffff817e9810-ffffffff817e9af7: end_unlink_async (STB_LOCAL)
ffffffff817f2a39-ffffffff817f2a4c: end_unlink_async.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181a6d0)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffffffff8181a6d0-ffffffff8181a9cb: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2670)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818f2670-ffffffff818f299d: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fb590)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818fb590-ffffffff818fb8bd: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818de350)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff818de350-ffffffff818de67d: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81979f00)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81979f00-ffffffff8197a22d: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad7640)
Location: drivers/usb/host/ehci-q.c:1312
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
**Symbols:**

```
ffffffff81ad7640-ffffffff81ad7972: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c623f0)
Location: drivers/usb/host/ehci-q.c:1312
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81c623f0-ffffffff81c62722: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc97e0)
Location: drivers/usb/host/ehci-q.c:1312
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81cc97e0-ffffffff81cc9b12: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7e6c0)
Location: drivers/usb/host/ehci-q.c:1312
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81d7e6c0-ffffffff81d7e9f2: end_unlink_async (STB_LOCAL)
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
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a56770)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffff800010a56770-ffff800010a56a08: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b26a58)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
c0b26a58-c0b26cf4: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b21080)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
c000000000b21080-c000000000b21404: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000674aca)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffffffe000674aca-ffffffe000674cce: end_unlink_async (STB_LOCAL)
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
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d2ab0)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffffffff817d2ab0-ffffffff817d2dab: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8180f550)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffffffff8180f550-ffffffff8180f84b: end_unlink_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void end_unlink_async(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182a020)
Location: drivers/usb/host/ehci-q.c:1311
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
```
**Symbols:**

```
ffffffff8182a020-ffffffff8182a31b: end_unlink_async (STB_LOCAL)
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
