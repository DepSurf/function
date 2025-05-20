# Function: <code>is_root_hub</code>

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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:116
Inline: True
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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:115
Inline: True
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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:116
Inline: True
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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:117
Inline: True
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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:104
Inline: True
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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:104
Inline: True
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
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:156
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bc99a)
Location: drivers/usb/core/usb.h:170
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff818ca307)
Location: drivers/usb/core/usb.h:170
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c96aa)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff818d5457)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818acfda)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff818b8a17)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8194206a)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff8194e4e7)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a99f28)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff81aa7496)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1e488)
Location: drivers/usb/core/usb.h:171
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2e316)
Location: drivers/usb/core/usb.h:171
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c85378)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff81c95506)
Location: drivers/usb/core/usb.h:172
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d39d78)
Location: drivers/usb/core/usb.h:173
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffff81d49fc6)
Location: drivers/usb/core/usb.h:173
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af4080)
Location: drivers/usb/core/usb.h:162
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (c0b0102c)
Location: drivers/usb/core/usb.h:162
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad5ffc)
Location: drivers/usb/core/usb.h:162
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (c000000000ae8480)
Location: drivers/usb/core/usb.h:162
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe00064092a)
Location: drivers/usb/core/usb.h:162
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/sysfs.c (ffffffe00064ca96)
Location: drivers/usb/core/usb.h:162
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/usb.h:162
Inline: True
```
</details>
</li>
</ul>

## Differences
