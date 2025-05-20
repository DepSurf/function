# Function: <code>bdi_cap_stable_pages_required</code>

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
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:204
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/backing-dev.h:204
Inline: True
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
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:205
Inline: True
```
```
In mm/backing-dev.c (ffffffff811c72d9)
Location: include/linux/backing-dev.h:205
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
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
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:205
Inline: True
```
```
In mm/backing-dev.c (ffffffff811d73f9)
Location: include/linux/backing-dev.h:205
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (0)
Location: include/linux/backing-dev.h:205
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
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:180
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e0229)
Location: include/linux/backing-dev.h:180
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (0)
Location: include/linux/backing-dev.h:180
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
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:185
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f622b)
Location: include/linux/backing-dev.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (0)
Location: include/linux/backing-dev.h:185
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
In mm/page-writeback.c (ffffffff811fc544)
Location: include/linux/backing-dev.h:186
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff812174f5)
Location: include/linux/backing-dev.h:186
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff8124d89c)
Location: include/linux/backing-dev.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/page-writeback.c (ffffffff8120ee34)
Location: include/linux/backing-dev.h:186
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff8122a405)
Location: include/linux/backing-dev.h:186
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff81261ce6)
Location: include/linux/backing-dev.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/page-writeback.c (ffffffff8121e5de)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff8123a085)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff8127cc36)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff818799b1)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffff8122c07e)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff81248385)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff8128c708)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff818ab7b1)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffff81259d6e)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff81276545)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff812bf1c6)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff8197ba81)
Location: include/linux/backing-dev.h:187
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/page-writeback.c (ffff8000102bae14)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffff8000102dd33c)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffff800010327e24)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffff800010b01fdc)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (c04e6ddc)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (c0502840)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (c053f0f0)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (c0be1230)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (c000000000373338)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (c00000000039cabc)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (c0000000003febb4)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (c000000000bf0de0)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffe0001ddbe2)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffe0001f59a2)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffe000227b46)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffe0006f1940)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffff812246ce)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff812409d5)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff81284ce8)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff81851631)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffff8121787e)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff812339d5)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff81276b58)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff81818c41)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffff8122246e)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff8123e775)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff81282af8)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff818a0c61)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/page-writeback.c (ffffffff81231a4e)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
```
```
In mm/backing-dev.c (ffffffff8124dea5)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/backing-dev.c:stable_pages_required_show
```
```
In mm/swapfile.c (ffffffff812927dd)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff818bcea1)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
```
</details>
</li>
</ul>

## Differences
