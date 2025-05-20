# Function: <code>remove_sysfs_files</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff816376ed)
Location: drivers/usb/host/ehci-sysfs.c:178
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff81698435)
Location: drivers/usb/host/ehci-sysfs.c:178
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c6965)
Location: drivers/usb/host/ehci-sysfs.c:178
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff816db125)
Location: drivers/usb/host/ehci-sysfs.c:178
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff81747855)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff81788069)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b0fd9)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff817eeec9)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181fda9)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f1a45)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fa965)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf036)
Location: drivers/devfreq/devfreq.c:1850
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818df245)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff819b4196)
Location: drivers/devfreq/devfreq.c:1868
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8197ac15)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff81a62d76)
Location: drivers/devfreq/devfreq.c:1868
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad348c)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd4227)
Location: drivers/devfreq/devfreq.c:1896
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5e0dc)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff81d81529)
Location: drivers/devfreq/devfreq.c:1898
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc574c)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff81def8e9)
Location: drivers/devfreq/devfreq.c:1899
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7a63c)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5ea9)
Location: drivers/devfreq/devfreq.c:1938
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In drivers/usb/host/ehci-hcd.c (ffff800010a59c0c)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (c0b2a074)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
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
In drivers/usb/host/ehci-hcd.c (c000000000b23f20)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffe000676664)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d8189)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff81814c29)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182e400)
Location: drivers/usb/host/ehci-sysfs.c:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_stop
```
</details>
</li>
</ul>

## Differences
