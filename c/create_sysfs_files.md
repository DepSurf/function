# Function: <code>create_sysfs_files</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff81634272)
Location: drivers/usb/host/ehci-sysfs.c:162
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169608a)
Location: drivers/usb/host/ehci-sysfs.c:162
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c416a)
Location: drivers/usb/host/ehci-sysfs.c:162
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff816d8924)
Location: drivers/usb/host/ehci-sysfs.c:162
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff81745054)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff81785761)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff817aecd1)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f2bdf)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff81823a12)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f550e)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c20203)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff819cef4c)
Location: drivers/devfreq/devfreq.c:1840
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819cef00-ffffffff819cef70: create_sysfs_files (STB_LOCAL)
ffffffff81c2f373-ffffffff81c2f3ad: create_sysfs_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c12240)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff819b40ac)
Location: drivers/devfreq/devfreq.c:1858
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819b4060-ffffffff819b40d0: create_sysfs_files (STB_LOCAL)
ffffffff81c21638-ffffffff81c21672: create_sysfs_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d1ebe1)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff81a62c8c)
Location: drivers/devfreq/devfreq.c:1858
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81a62c40-ffffffff81a62cb0: create_sysfs_files (STB_LOCAL)
ffffffff81d331a1-ffffffff81d331db: create_sysfs_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81eea6c1)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd4118)
Location: drivers/devfreq/devfreq.c:1886
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81bd40c0-ffffffff81bd4148: create_sysfs_files (STB_LOCAL)
ffffffff81eff63c-ffffffff81eff676: create_sysfs_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5c613)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff81d80280)
Location: drivers/devfreq/devfreq.c:1888
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81d80280-ffffffff81d8031e: create_sysfs_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3c93)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff81dee610)
Location: drivers/devfreq/devfreq.c:1889
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81dee610-ffffffff81dee6ae: create_sysfs_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int create_sysfs_files(struct ehci_hcd *ehci);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d78b8b)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea4ac0)
Location: drivers/devfreq/devfreq.c:1928
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ea4ac0-ffffffff81ea4b5e: create_sysfs_files (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a56368)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (c0b2bdfc)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (c000000000b209b4)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffe0006758ba)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff817dbdf2)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff81818892)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
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
In drivers/usb/host/ehci-hcd.c (ffffffff81832882)
Location: drivers/usb/host/ehci-sysfs.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
