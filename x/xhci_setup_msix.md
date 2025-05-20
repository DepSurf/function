# Function: <code>xhci_setup_msix</code>

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
In drivers/usb/host/xhci.c (ffffffff8164cf64)
Location: drivers/usb/host/xhci.c:277
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
In drivers/usb/host/xhci.c (ffffffff816ad894)
Location: drivers/usb/host/xhci.c:279
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_setup_msix(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dac00)
Location: drivers/usb/host/xhci.c:285
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff816dac00-ffffffff816dad92: xhci_setup_msix (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816f02cb)
Location: drivers/usb/host/xhci.c:256
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff8175c48b)
Location: drivers/usb/host/xhci.c:246
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff8179ce7c)
Location: drivers/usb/host/xhci.c:323
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff817c325c)
Location: drivers/usb/host/xhci.c:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff818024a7)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/usb/host/xhci.c (ffffffff81831327)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_setup_msix(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81903630)
Location: drivers/usb/host/xhci.c:322
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff81903630-ffffffff8190375c: xhci_setup_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_setup_msix(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190bba0)
Location: drivers/usb/host/xhci.c:322
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff8190bba0-ffffffff8190bccc: xhci_setup_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818ef30c)
Location: drivers/usb/host/xhci.c:325
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198becc)
Location: drivers/usb/host/xhci.c:325
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ae80b3)
Location: drivers/usb/host/xhci.c:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c74073)
Location: drivers/usb/host/xhci.c:328
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/usb/host/xhci.c (ffff800010a6d830)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/usb/host/xhci.c (c0b41ecc)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/usb/host/xhci.c (c000000000b418d0)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/usb/host/xhci.c (ffffffe000686cba)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/usb/host/xhci.c (ffffffff817e9707)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817ae817)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818261a7)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/usb/host/xhci.c (ffffffff81840087)
Location: drivers/usb/host/xhci.c:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
</ul>
