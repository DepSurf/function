# Function: <code>ehci_handover_companion_ports</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff81638a51)
Location: drivers/usb/host/ehci-hub.c:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff81699737)
Location: drivers/usb/host/ehci-hub.c:47
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c7817)
Location: drivers/usb/host/ehci-hub.c:47
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff816dc01a)
Location: drivers/usb/host/ehci-hub.c:47
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174874a)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178bac7)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b22c7)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f1981)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff81822871)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f4c00)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff818f4c00-ffffffff818f4ede: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fdb40)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff818fdb40-ffffffff818fde1e: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818e0d30)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff818e0d30-ffffffff818e100e: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8197c1b0)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff8197c1b0-ffffffff8197c52a: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad4a80)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff81ad4a80-ffffffff81ad4dcf: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5f6e0)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff81c5f6e0-ffffffff81c5fa2f: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc6b60)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff81cc6b60-ffffffff81cc6e8e: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ehci_handover_companion_ports(struct ehci_hcd *ehci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7b9f0)
Location: drivers/usb/host/ehci-hub.c:33
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
**Symbols:**

```
ffffffff81d7b9f0-ffffffff81d7bd1e: ehci_handover_companion_ports (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a5db70)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2d450)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b2b790)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000678cca)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
</details>
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
In drivers/usb/host/ehci-hcd.c (ffffffff817dac51)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818176f1)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff81831730)
Location: drivers/usb/host/ehci-hub.c:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
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
