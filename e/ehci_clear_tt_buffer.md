# Function: <code>ehci_clear_tt_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81632150)
Location: drivers/usb/host/ehci-q.c:160
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81632150-ffffffff8163220c: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81692da0)
Location: drivers/usb/host/ehci-q.c:164
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81692da0-ffffffff81692e59: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c0d20)
Location: drivers/usb/host/ehci-q.c:164
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff816c0d20-ffffffff816c0dd9: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d5330)
Location: drivers/usb/host/ehci-q.c:164
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff816d5330-ffffffff816d53e4: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81741a20)
Location: drivers/usb/host/ehci-q.c:151
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81741a20-ffffffff81741ad4: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81781ee0)
Location: drivers/usb/host/ehci-q.c:151
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81781ee0-ffffffff81781f93: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817a8700)
Location: drivers/usb/host/ehci-q.c:151
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff817a8700-ffffffff817a87b3: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817e7960)
Location: drivers/usb/host/ehci-q.c:151
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff817e7960-ffffffff817e7a12: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81818820)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81818820-ffffffff818188d2: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818e9980)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818e9980-ffffffff818e9a32: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2870)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818f2870-ffffffff818f2922: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818d6030)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818d6030-ffffffff818d60e2: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81970ce0)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81970ce0-ffffffff81970d8f: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81acbad0)
Location: drivers/usb/host/ehci-q.c:156
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81acbad0-ffffffff81acbb96: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c56220)
Location: drivers/usb/host/ehci-q.c:156
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81c56220-ffffffff81c562f1: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbd850)
Location: drivers/usb/host/ehci-q.c:156
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81cbd850-ffffffff81cbd927: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d725c0)
Location: drivers/usb/host/ehci-q.c:156
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81d725c0-ffffffff81d72697: ehci_clear_tt_buffer (STB_LOCAL)
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
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a51b68)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffff800010a51b68-ffff800010a51c34: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b25624)
Location: drivers/usb/host/ehci-q.c:155
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
c0b25624-c0b25704: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1af70)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
c000000000b1af70-c000000000b1b09c: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00066efec)
Location: drivers/usb/host/ehci-q.c:155
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffe00066efec-ffffffe00066f0a4: ehci_clear_tt_buffer (STB_LOCAL)
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
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d0c00)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff817d0c00-ffffffff817d0cb2: ehci_clear_tt_buffer (STB_LOCAL)
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
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8180d6a0)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff8180d6a0-ffffffff8180d752: ehci_clear_tt_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ehci_clear_tt_buffer(struct ehci_hcd *ehci, struct ehci_qh *qh, struct urb *urb, u32 token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81827d30)
Location: drivers/usb/host/ehci-q.c:155
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81827d30-ffffffff81827de2: ehci_clear_tt_buffer (STB_LOCAL)
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
