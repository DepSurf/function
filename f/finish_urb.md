# Function: <code>finish_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8163dfc0)
Location: drivers/usb/host/ohci-q.c:40
Inline: False
```
**Symbols:**

```
ffffffff8163dfc0-ffffffff8163e105: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8169ebe0)
Location: drivers/usb/host/ohci-q.c:40
Inline: False
```
**Symbols:**

```
ffffffff8169ebe0-ffffffff8169ed30: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816ccd30)
Location: drivers/usb/host/ohci-q.c:40
Inline: False
```
**Symbols:**

```
ffffffff816ccd30-ffffffff816cce80: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e1830)
Location: drivers/usb/host/ohci-q.c:40
Inline: False
```
**Symbols:**

```
ffffffff816e1830-ffffffff816e1989: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8174e030)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff8174e030-ffffffff8174e189: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81791960)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff81791960-ffffffff81791ab7: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817b7f30)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff817b7f30-ffffffff817b8087: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817f6aa0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff817f6aa0-ffffffff817f6c02: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81827900)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff81827900-ffffffff81827a62: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818fa3a0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff818fa3a0-ffffffff818fa502: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81902ee0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81902ee0-ffffffff81903042: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e65f0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff818e65f0-ffffffff818e674f: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff819829b0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff819829b0-ffffffff81982b0f: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81adacd0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81adacd0-ffffffff81adae30: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c65f00)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81c65f00-ffffffff81c66060: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81ccd180)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81ccd180-ffffffff81ccd2df: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d82080)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81d82080-ffffffff81d821df: finish_urb (STB_LOCAL)
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
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffff800010a606a8)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffff800010a606a8-ffff800010a60864: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c0b31434)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
c0b31434-c0b315ac: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c000000000b2db00)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
c000000000b2db00-c000000000b2dd40: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffe00067db1c)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffe00067db1c-ffffffe00067dcb8: finish_urb (STB_LOCAL)
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
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817dfce0)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff817dfce0-ffffffff817dfe42: finish_urb (STB_LOCAL)
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
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8181c780)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff8181c780-ffffffff8181c8e2: finish_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void finish_urb(struct ohci_hcd *ohci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81834170)
Location: drivers/usb/host/ohci-q.c:41
Inline: False
```
**Symbols:**

```
ffffffff81834170-ffffffff818342c2: finish_urb (STB_LOCAL)
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
