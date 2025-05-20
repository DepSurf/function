# Function: <code>ratelimit_default_init</code>

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
In kernel/printk/printk.c (ffffffff810ddcef)
Location: include/linux/ratelimit.h:49
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
In kernel/printk/printk.c (ffffffff810e42ff)
Location: include/linux/ratelimit.h:49
Inline: True
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
In kernel/printk/printk.c (ffffffff810e257f)
Location: include/linux/ratelimit.h:49
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c97f7)
Location: include/linux/ratelimit.h:49
Inline: True
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
In kernel/printk/printk.c (ffffffff810ea35f)
Location: include/linux/ratelimit.h:50
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162feff)
Location: include/linux/ratelimit.h:50
Inline: True
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
In kernel/printk/printk.c (ffffffff810f290b)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166abf6)
Location: include/linux/ratelimit.h:50
Inline: True
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
In kernel/printk/printk.c (ffffffff810fdf4b)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff81689300)
Location: include/linux/ratelimit.h:50
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
In kernel/printk/printk.c (ffffffff8110667b)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c05de)
Location: include/linux/ratelimit.h:50
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
In kernel/printk/printk.c (ffffffff81112a0b)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e362b)
Location: include/linux/ratelimit.h:50
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
In kernel/printk/printk.c (ffffffff8111e2cd)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff817957e2)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_dev_data
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
In kernel/printk/printk.c (ffffffff81118d5b)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a3d62)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_dev_data
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
In kernel/printk/printk.c (ffffffff8111930b)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81787f9d)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/printk/printk.c (ffffffff811396cb)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180eb6d)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/printk/printk.c (ffffffff8115c19b)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81950b96)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/printk/printk.c (ffffffff8118ec2b)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5446)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/printk/printk.c (ffffffff811a03bb)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b01596)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/printk/printk.c (ffffffff811af3db)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b54653)
Location: include/linux/ratelimit.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/printk/printk.c (ffff8000101732b0)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
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
In kernel/printk/printk.c (c03c5690)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
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
In kernel/printk/printk.c (c0000000001cdbc0)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
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
In kernel/printk/printk.c (ffffffe00010f136)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
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
In kernel/printk/printk.c (ffffffff8110afeb)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a907b)
Location: include/linux/ratelimit.h:50
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
In kernel/printk/printk.c (ffffffff810fbe7b)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686a6b)
Location: include/linux/ratelimit.h:50
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
In kernel/printk/printk.c (ffffffff81108edb)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d72eb)
Location: include/linux/ratelimit.h:50
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
In kernel/printk/printk.c (ffffffff8111410b)
Location: include/linux/ratelimit.h:50
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f189b)
Location: include/linux/ratelimit.h:50
Inline: True
```
</details>
</li>
</ul>

## Differences
