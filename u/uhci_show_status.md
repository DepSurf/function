# Function: <code>uhci_show_status</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff81646b51)
Location: drivers/usb/host/uhci-debug.c:304
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff816a7683)
Location: drivers/usb/host/uhci-debug.c:304
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d57a3)
Location: drivers/usb/host/uhci-debug.c:304
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff816e9989)
Location: drivers/usb/host/uhci-debug.c:304
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff81756175)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817964d6)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bcde6)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817fbfd6)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182ce26)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fdb10)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff818fdb10-ffffffff818fde04: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819063f0)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff819063f0-ffffffff819066e4: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9a00)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff818e9a00-ffffffff818e9cf3: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819860a0)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff819860a0-ffffffff81986393: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae1f80)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff81ae1f80-ffffffff81ae229d: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6d980)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff81c6d980-ffffffff81c6dc9d: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd4f90)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff81cd4f90-ffffffff81cd52aa: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d89f70)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
ffffffff81d89f70-ffffffff81d8a28a: uhci_show_status (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffff800010a68628)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3d504)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
c0b3d504-c0b3dac8: uhci_show_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uhci_show_status(struct uhci_hcd *uhci, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3d1b0)
Location: drivers/usb/host/uhci-debug.c:305
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
**Symbols:**

```
c000000000b3d1b0-c000000000b3daf0: uhci_show_status (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffffffe0006831e6)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e5206)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff81821ca6)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183c376)
Location: drivers/usb/host/uhci-debug.c:305
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
<b>Arch</b>
<ul>
</ul>
