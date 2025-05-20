# Function: <code>dbg_status</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169b4b0)
Location: drivers/usb/host/ehci-dbg.c:271
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c9590)
Location: drivers/usb/host/ehci-dbg.c:271
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff816ddf02)
Location: drivers/usb/host/ehci-dbg.c:271
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174a642)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178a5bb)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ae20b)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f2c66)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff81823a99)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1ab7)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
ffffffff818ebb20-ffffffff818ebb83: dbg_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fa9d7)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
ffffffff818f49f0-ffffffff818f4a53: dbg_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818df2b7)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
ffffffff818d7fb0-ffffffff818d8013: dbg_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8197ac87)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
ffffffff81972dd0-ffffffff81972e30: dbg_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad34f9)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
ffffffff81ace5d0-ffffffff81ace651: dbg_status (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c63e2c)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ccb222)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d800d8)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a59cb8)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
ffff800010a53788-ffff800010a53800: dbg_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dbg_status(struct ehci_hcd *ehci, const char *label, u32 status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2a0f0)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
```
**Symbols:**

```
c0b27c00-c0b27c88: dbg_status (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (c000000000b26e04)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffe000677182)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff817dbe79)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff81818919)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff81832909)
Location: drivers/usb/host/ehci-dbg.c:261
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
</ul>
<b>Arch</b>
<ul>
</ul>
