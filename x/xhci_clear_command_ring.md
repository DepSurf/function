# Function: <code>xhci_clear_command_ring</code>

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
In drivers/usb/host/xhci.c (ffffffff8164cb02)
Location: drivers/usb/host/xhci.c:814
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff816ad43a)
Location: drivers/usb/host/xhci.c:821
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff816db71a)
Location: drivers/usb/host/xhci.c:824
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff816efd8d)
Location: drivers/usb/host/xhci.c:787
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff8175bf3a)
Location: drivers/usb/host/xhci.c:785
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff8179c9f9)
Location: drivers/usb/host/xhci.c:854
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff817c2c27)
Location: drivers/usb/host/xhci.c:853
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff818028e9)
Location: drivers/usb/host/xhci.c:851
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff818337e9)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_clear_command_ring(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81903ca0)
Location: drivers/usb/host/xhci.c:848
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_suspend
```
**Symbols:**

```
ffffffff81903ca0-ffffffff81903d30: xhci_clear_command_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_clear_command_ring(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190c110)
Location: drivers/usb/host/xhci.c:848
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_suspend
```
**Symbols:**

```
ffffffff8190c110-ffffffff8190c1a0: xhci_clear_command_ring (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff818f2580)
Location: drivers/usb/host/xhci.c:851
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff8198f7d8)
Location: drivers/usb/host/xhci.c:851
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81aebce2)
Location: drivers/usb/host/xhci.c:888
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81c782e2)
Location: drivers/usb/host/xhci.c:885
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81cdf3bf)
Location: drivers/usb/host/xhci.c:729
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81d9433f)
Location: drivers/usb/host/xhci.c:768
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffff800010a70844)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (c0b44798)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (c000000000b44f3c)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffe000688fc6)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff817ebbc1)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff817b0cd9)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81828669)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81842639)
Location: drivers/usb/host/xhci.c:848
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
