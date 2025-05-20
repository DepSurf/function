# Function: <code>device_disable_async_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8144551f)
Location: include/linux/device.h:932
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff815536b3)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814916a9)
Location: include/linux/device.h:948
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff815a56b3)
Location: include/linux/device.h:948
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b2f19)
Location: include/linux/device.h:1057
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff815d3e73)
Location: include/linux/device.h:1057
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8162f5b1)
Location: include/linux/device.h:1057
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814bd38f)
Location: include/linux/device.h:1061
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff815e89f8)
Location: include/linux/device.h:1061
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8164467c)
Location: include/linux/device.h:1061
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fd71f)
Location: include/linux/device.h:1059
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff8164fd08)
Location: include/linux/device.h:1059
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff816ad60f)
Location: include/linux/device.h:1059
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152df6d)
Location: include/linux/device.h:1104
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff8168b3a1)
Location: include/linux/device.h:1104
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff816e9f4a)
Location: include/linux/device.h:1104
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81544dbd)
Location: include/linux/device.h:1157
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816ab5d1)
Location: include/linux/device.h:1157
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8170d9bf)
Location: include/linux/device.h:1157
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81577061)
Location: include/linux/device.h:1180
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816e517f)
Location: include/linux/device.h:1180
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8174920c)
Location: include/linux/device.h:1180
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff815987bb)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff8170945f)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8176d35c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81647101)
Location: include/linux/device.h:729
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817c44af)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8182f926)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81bfacd2)
Location: include/linux/device.h:697
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817d8f8f)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81c16438)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81becb2e)
Location: include/linux/device.h:703
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817bd35f)
Location: include/linux/device.h:703
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81c08142)
Location: include/linux/device.h:703
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81ce7823)
Location: include/linux/device.h:720
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff818476df)
Location: include/linux/device.h:720
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81d0bfc6)
Location: include/linux/device.h:720
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81eae994)
Location: include/linux/device.h:795
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff8198c1fb)
Location: include/linux/device.h:795
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81ed4f02)
Location: include/linux/device.h:795
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff81908fad)
Location: include/linux/device.h:792
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff81afbcdb)
Location: include/linux/device.h:792
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81b76edb)
Location: include/linux/device.h:792
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff8194c62e)
Location: include/linux/device.h:918
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a0cb)
Location: include/linux/device.h:918
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81bcab6b)
Location: include/linux/device.h:918
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff819958fe)
Location: include/linux/device.h:950
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff81ba24bb)
Location: include/linux/device.h:950
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81c1f79b)
Location: include/linux/device.h:950
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffff8000106fd13c)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (ffff8000108f728c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffff80001096fa18)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (c08956e8)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (c09e31fc)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (c0a44c8c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (c00000000087b8d0)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (c0000000009929c8)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (c000000000a290c8)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffe0004ccd00)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffe0005d99ec)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff8158c64b)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816cebaf)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81721a4c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff8157b18b)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816a9edf)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff816fae7c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff8158c50b)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff816fd11f)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8176081c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
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
In drivers/pci/quirks.c (ffffffff815a69bb)
Location: include/linux/device.h:1422
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff817179af)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8177be7c)
Location: include/linux/device.h:1422
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
</details>
</li>
</ul>

## Differences
