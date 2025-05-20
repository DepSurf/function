# Function: <code>dev_get_uevent_suppress</code>

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
In block/partition-generic.c (0)
Location: include/linux/device.h:911
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
In block/partition-generic.c (0)
Location: include/linux/device.h:927
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
In block/partition-generic.c (0)
Location: include/linux/device.h:1036
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
In block/partition-generic.c (0)
Location: include/linux/device.h:1040
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
In block/partition-generic.c (0)
Location: include/linux/device.h:1038
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
In block/partition-generic.c (ffffffff81499b1d)
Location: include/linux/device.h:1083
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/partition-generic.c (ffffffff814b3df9)
Location: include/linux/device.h:1136
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/partition-generic.c (ffffffff814e231b)
Location: include/linux/device.h:1159
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
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
In block/partition-generic.c (ffffffff814fb6db)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff817faaa6)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff8155d658)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff818cad46)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff815793c8)
Location: include/linux/device.h:676
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff818d5e36)
Location: include/linux/device.h:676
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff815813f6)
Location: include/linux/device.h:682
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff818b9376)
Location: include/linux/device.h:682
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff815e67b5)
Location: include/linux/device.h:699
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff8194ee56)
Location: include/linux/device.h:699
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff816956da)
Location: include/linux/device.h:774
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff81aa7f26)
Location: include/linux/device.h:774
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff81754880)
Location: include/linux/device.h:771
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff81c2ef36)
Location: include/linux/device.h:771
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff81790980)
Location: include/linux/device.h:897
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff81c96196)
Location: include/linux/device.h:897
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partitions/core.c (ffffffff817d4233)
Location: include/linux/device.h:929
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff81d4ac76)
Location: include/linux/device.h:929
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (ffff8000105fd6a0)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffff800010a2c424)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (c07a8574)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (c0b01b78)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (c000000000796f78)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (c000000000ae94f8)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (ffffffe000439250)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffe00064d526)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (ffffffff814f3cbb)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff817b2e86)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (ffffffff814e41cb)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff817a48b6)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (ffffffff814efd4b)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff817ef926)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
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
In block/partition-generic.c (ffffffff81508ddb)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In drivers/usb/core/devio.c (ffffffff81809b66)
Location: include/linux/device.h:1401
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
</details>
</li>
</ul>

## Differences
