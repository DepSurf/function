# Function: <code>xhci_create_usb3_bos_desc</code>

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
In drivers/usb/host/xhci-hub.c (ffffffff8165e00a)
Location: drivers/usb/host/xhci-hub.c:67
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff816be71a)
Location: drivers/usb/host/xhci-hub.c:67
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff816ec5ca)
Location: drivers/usb/host/xhci-hub.c:67
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff81700bea)
Location: drivers/usb/host/xhci-hub.c:67
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff8176d896)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817ae598)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817d4754)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff81814c93)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff81845ebf)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_create_usb3_bos_desc(struct xhci_hcd *xhci, char *buf, u16 wLength);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81917640)
Location: drivers/usb/host/xhci-hub.c:55
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81917640-ffffffff819179fb: xhci_create_usb3_bos_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_create_usb3_bos_desc(struct xhci_hcd *xhci, char *buf, u16 wLength);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8191df70)
Location: drivers/usb/host/xhci-hub.c:55
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8191df70-ffffffff8191e329: xhci_create_usb3_bos_desc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffe00069a8ea)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817fe26f)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817c340f)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff8183ad3f)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff818551cf)
Location: drivers/usb/host/xhci-hub.c:55
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
