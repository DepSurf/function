# Function: <code>blkcg_cgwb_put</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122c01e)
Location: include/linux/blk-cgroup.h:451
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff814c3092)
Location: include/linux/blk-cgroup.h:451
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffff8123bcc1)
Location: include/linux/blk-cgroup.h:458
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff814f16d3)
Location: include/linux/blk-cgroup.h:458
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffff8124a171)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff8150acc3)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In mm/backing-dev.c (ffff8000102df9ac)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffff80001060e4e8)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (c0504734)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (c07b8dd4)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (c00000000039f590)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (c0000000007ab95c)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffe0001f765e)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffe0004469fe)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffff812427c1)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff815032a3)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffff81235791)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff814f3773)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffff81240561)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff814ff333)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
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
In mm/backing-dev.c (ffffffff8124fc85)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff81518493)
Location: include/linux/blk-cgroup.h:460
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
</details>
</li>
</ul>

## Differences
