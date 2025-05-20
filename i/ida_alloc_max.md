# Function: <code>ida_alloc_max</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8134c27e)
Location: include/linux/idr.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff81374c52)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff8138ced2)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff813d8322)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813e9fc2)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff813f0afe)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff814429ee)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff814be77a)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81a5ecbc)
Location: include/linux/idr.h:307
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff81a77de4)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_create_group
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
In fs/devpts/inode.c (ffffffff815565fa)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In block/bsg.c (ffffffff8175ee01)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/misc.c (ffffffff81a95ec3)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/dax/super.c (ffffffff81b65657)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81be9b3c)
Location: include/linux/idr.h:307
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81cd2055)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
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
In fs/devpts/inode.c (ffffffff8158e3ba)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In block/bsg.c (ffffffff8179dd01)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/misc.c (ffffffff81ae16d3)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/dax/super.c (ffffffff81bb8c77)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81c41f6c)
Location: include/linux/idr.h:307
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81d39ad5)
Location: include/linux/idr.h:307
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
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
In fs/devpts/inode.c (ffffffff815c70ea)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In block/bsg.c (ffffffff817e1780)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/misc.c (ffffffff81b34ac3)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/dax/super.c (ffffffff81c0d2d7)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87c70)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81cf762c)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81defed5)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
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
In fs/devpts/inode.c (ffff80001045eb5c)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (c061f5d8)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e2dfc)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:vas_window_alloc
```
```
In fs/devpts/inode.c (c00000000057acc0)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffe0002ee750)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff813854b2)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff81375f42)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff81382f82)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
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
In fs/devpts/inode.c (ffffffff81396aa2)
Location: include/linux/idr.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
</details>
</li>
</ul>

## Differences
