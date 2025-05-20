# Function: <code>periodic_link</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff8163e22f)
Location: drivers/usb/host/ohci-q.c:142
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff8169ee6a)
Location: drivers/usb/host/ohci-q.c:142
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff816ccfba)
Location: drivers/usb/host/ohci-q.c:142
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e14ac)
Location: drivers/usb/host/ohci-q.c:142
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff8174dcac)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff8178e4ab)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b4b2b)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f42da)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81824f3a)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void periodic_link(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818f6ce0)
Location: drivers/usb/host/ohci-q.c:143
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
```
**Symbols:**

```
ffffffff818f6ce0-ffffffff818f6e07: periodic_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void periodic_link(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818ff830)
Location: drivers/usb/host/ohci-q.c:143
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
```
**Symbols:**

```
ffffffff818ff830-ffffffff818ff957: periodic_link (STB_LOCAL)
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
In drivers/usb/host/ohci-hcd.c (ffffffff818e2e79)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff8197eff5)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81ada84e)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81c65a4e)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81ccccc4)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81d81bc4)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffff800010a5f6dc)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (c0b3169c)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (c000000000b2d590)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067a09e)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff817dd31a)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81819dba)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
In drivers/usb/host/ohci-hcd.c (ffffffff81833daa)
Location: drivers/usb/host/ohci-q.c:143
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_schedule
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
