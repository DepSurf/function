# Function: <code>xhci_pending_portevent</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179d704)
Location: drivers/usb/host/xhci.c:926
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff817c3af1)
Location: drivers/usb/host/xhci.c:925
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff8180333e)
Location: drivers/usb/host/xhci.c:932
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff818345e0)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff819033e0)
Location: drivers/usb/host/xhci.c:929
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff819033e0-ffffffff81903471: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190c910)
Location: drivers/usb/host/xhci.c:927
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff8190c910-ffffffff8190c9a1: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818efe80)
Location: drivers/usb/host/xhci.c:930
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff818efe80-ffffffff818eff14: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198ca90)
Location: drivers/usb/host/xhci.c:930
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff8198ca90-ffffffff8198cb24: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ae7a70)
Location: drivers/usb/host/xhci.c:967
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81ae7a70-ffffffff81ae7b1c: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c739a0)
Location: drivers/usb/host/xhci.c:964
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81c739a0-ffffffff81c73a4c: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdaf30)
Location: drivers/usb/host/xhci.c:808
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81cdaf30-ffffffff81cdafd2: xhci_pending_portevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d8ff60)
Location: drivers/usb/host/xhci.c:847
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81d8ff60-ffffffff81d90002: xhci_pending_portevent (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a71c88)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (c0b459d4)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (c000000000b46d24)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffe00068a286)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff817ec998)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff817b1aa4)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff81829460)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
In drivers/usb/host/xhci.c (ffffffff818433fe)
Location: drivers/usb/host/xhci.c:929
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
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
