# Function: <code>uhci_set_next_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816449b0)
Location: drivers/usb/host/uhci-q.c:28
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff816449b0-ffffffff816449e8: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a54f0)
Location: drivers/usb/host/uhci-q.c:28
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff816a54f0-ffffffff816a5528: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d35f0)
Location: drivers/usb/host/uhci-q.c:28
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff816d35f0-ffffffff816d3628: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e7cb0)
Location: drivers/usb/host/uhci-q.c:28
Inline: False
```
**Symbols:**

```
ffffffff816e7cb0-ffffffff816e7ce8: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81754490)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
```
**Symbols:**

```
ffffffff81754490-ffffffff817544c8: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81794ad0)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff81794ad0-ffffffff81794b16: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817baf90)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817baf90-ffffffff817bafd6: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817fa8c0)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817fa8c0-ffffffff817fa906: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182b700)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff8182b700-ffffffff8182b746: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ffe18)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819086e8)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ebec7)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
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
In drivers/usb/host/uhci-hcd.c (ffffffff819885d7)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae514d)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c70d5d)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd833d)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d34d)
Location: drivers/usb/host/uhci-q.c:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
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
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a66f78)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffff800010a66f78-ffff800010a66fe0: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b38c78)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
c0b38c78-c0b38cc8: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b37e60)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
c000000000b37e60-c000000000b37ef4: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000681088)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffe000681088-ffffffe0006810d0: uhci_set_next_interrupt (STB_LOCAL)
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
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e3ae0)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817e3ae0-ffffffff817e3b26: uhci_set_next_interrupt (STB_LOCAL)
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
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81820580)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff81820580-ffffffff818205c6: uhci_set_next_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_set_next_interrupt(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183a690)
Location: drivers/usb/host/uhci-q.c:29
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff8183a690-ffffffff8183a6d6: uhci_set_next_interrupt (STB_LOCAL)
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
