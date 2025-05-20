# Function: <code>ohci_hub_descriptor</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff8163e668)
Location: drivers/usb/host/ohci-hub.c:532
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff8169f270)
Location: drivers/usb/host/ohci-hub.c:532
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff816cd3c0)
Location: drivers/usb/host/ohci-hub.c:532
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e1b4b)
Location: drivers/usb/host/ohci-hub.c:532
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff8174e350)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff8178e9a7)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b5027)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f4790)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff818255f0)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ohci_hub_descriptor(struct ohci_hcd *ohci, struct usb_hub_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818f8f60)
Location: drivers/usb/host/ohci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
**Symbols:**

```
ffffffff818f8f60-ffffffff818f9062: ohci_hub_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ohci_hub_descriptor(struct ohci_hcd *ohci, struct usb_hub_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81901aa0)
Location: drivers/usb/host/ohci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
**Symbols:**

```
ffffffff81901aa0-ffffffff81901ba2: ohci_hub_descriptor (STB_LOCAL)
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
In drivers/usb/host/ohci-hcd.c (ffffffff818e6249)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff81982609)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff81ae061e)
Location: drivers/usb/host/ohci-hub.c:538
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff81c6bd2e)
Location: drivers/usb/host/ohci-hub.c:538
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff81cd3213)
Location: drivers/usb/host/ohci-hub.c:538
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff81d881d3)
Location: drivers/usb/host/ohci-hub.c:538
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffff800010a643fc)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (c0b31bd0)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (c000000000b331ac)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067a818)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff817dd9d0)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff8181a470)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
In drivers/usb/host/ohci-hcd.c (ffffffff818345c0)
Location: drivers/usb/host/ohci-hub.c:535
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
