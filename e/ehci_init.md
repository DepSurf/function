# Function: <code>ehci_init</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff81637910)
Location: drivers/usb/host/ehci-hcd.c:456
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169861d)
Location: drivers/usb/host/ehci-hcd.c:465
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c6b4d)
Location: drivers/usb/host/ehci-hcd.c:465
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff816db31a)
Location: drivers/usb/host/ehci-hcd.c:465
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff81747a4a)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178826c)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b144c)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f20d9)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff81822fc9)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ee1c0)
Location: drivers/usb/host/ehci-hcd.c:453
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff818ee1c0-ffffffff818ee471: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f70e0)
Location: drivers/usb/host/ehci-hcd.c:453
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff818f70e0-ffffffff818f7391: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818da6d0)
Location: drivers/usb/host/ehci-hcd.c:453
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff818da6d0-ffffffff818da980: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81975a80)
Location: drivers/usb/host/ehci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81975a80-ffffffff81975d2d: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1520)
Location: drivers/usb/host/ehci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81ad1520-ffffffff81ad17e8: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5bd70)
Location: drivers/usb/host/ehci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81c5bd70-ffffffff81c5c038: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3620)
Location: drivers/usb/host/ehci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81cc3620-ffffffff81cc38e8: ehci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ehci_init(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d78520)
Location: drivers/usb/host/ehci-hcd.c:454
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81d78520-ffffffff81d787e8: ehci_init (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (c0b2ee64)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (c000000000b291dc)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffe00067689c)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817db3a9)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff81817e49)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff81831e39)
Location: drivers/usb/host/ehci-hcd.c:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
