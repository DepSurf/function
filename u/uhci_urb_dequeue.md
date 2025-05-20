# Function: <code>uhci_urb_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81645fc0)
Location: drivers/usb/host/uhci-q.c:1482
Inline: False
```
**Symbols:**

```
ffffffff81645fc0-ffffffff8164617a: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a6ae0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff816a6ae0-ffffffff816a6cab: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d4c00)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff816d4c00-ffffffff816d4dcb: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb510)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff816eb510-ffffffff816eb696: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81757d00)
Location: drivers/usb/host/uhci-q.c:1482
Inline: False
```
**Symbols:**

```
ffffffff81757d00-ffffffff81757e86: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81797210)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81797210-ffffffff8179738c: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bc2f0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff817bc2f0-ffffffff817bc46c: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff817fb4c0-ffffffff817fb642: uhci_urb_dequeue (STB_LOCAL)
ffffffff81800009-ffffffff81800034: uhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182c320)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff8182c320-ffffffff8182c496: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ffeb0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff818ffeb0-ffffffff818fff8f: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908780)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81908780-ffffffff8190885f: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ebf50)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff818ebf50-ffffffff818ec0d5: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81988660)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81988660-ffffffff819887e5: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5cf0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81ae5cf0-ffffffff81ae5e89: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c71a40)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81c71a40-ffffffff81c71bd9: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9010)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81cd9010-ffffffff81cd91af: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8e020)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81d8e020-ffffffff81d8e1bf: uhci_urb_dequeue (STB_LOCAL)
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
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a6b368)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffff800010a6b368-ffff800010a6b54c: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3c450)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
c0b3c450-c0b3c60c: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3b6b0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
c000000000b3b6b0-c000000000b3b8bc: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe0006825c4)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffe0006825c4-ffffffe000682716: uhci_urb_dequeue (STB_LOCAL)
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
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e4700)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff817e4700-ffffffff817e4876: uhci_urb_dequeue (STB_LOCAL)
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
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818211a0)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff818211a0-ffffffff81821316: uhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b870)
Location: drivers/usb/host/uhci-q.c:1481
Inline: False
```
**Symbols:**

```
ffffffff8183b870-ffffffff8183b9e6: uhci_urb_dequeue (STB_LOCAL)
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
