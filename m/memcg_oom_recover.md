# Function: <code>memcg_oom_recover</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff811fa5b0)
Location: mm/memcontrol.c:1673
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff811fa5b0-ffffffff811fa5d1: memcg_oom_recover.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812213eb)
Location: mm/memcontrol.c:1538
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8121dde0-ffffffff8121de01: memcg_oom_recover.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81233b5b)
Location: mm/memcontrol.c:1509
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812303c0-ffffffff812303e1: memcg_oom_recover.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8123f3ce)
Location: mm/memcontrol.c:1501
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8123bcd0-ffffffff8123bcf1: memcg_oom_recover.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8125f155)
Location: mm/memcontrol.c:1515
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8125b340-ffffffff8125b361: memcg_oom_recover.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81283505)
Location: mm/memcontrol.c:1472
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8127f090-ffffffff8127f0b1: memcg_oom_recover.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81297075)
Location: mm/memcontrol.c:1653
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812938d0-ffffffff812938f1: memcg_oom_recover.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2cb5)
Location: mm/memcontrol.c:1854
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812af010-ffffffff812af031: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812c4785)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c0a70-ffffffff812c0a91: memcg_oom_recover.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812f9818)
Location: mm/memcontrol.c:1736
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff813055a8)
Location: mm/memcontrol.c:1925
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff8130cc2f)
Location: mm/memcontrol.c:1748
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff813575b0)
Location: mm/memcontrol.c:1800
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff813d0b48)
Location: mm/memcontrol.c:1817
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81455a31)
Location: mm/memcontrol.c:1877
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff8148b851)
Location: mm/memcontrol.c:1911
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
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
In mm/memcontrol.c (ffffffff814bb0e1)
Location: mm/memcontrol.c:1983
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffff8000103673c0)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffff800010362090-ffff8000103620d0: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c0558b00)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c05549f8-c0554a28: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c0000000004548d4)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c00000000044eb60-c00000000044eba8: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe000245576)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffe000241870-ffffffe0002418a6: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812bcd65)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812b9050-ffffffff812b9071: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812adeb5)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812aa2e0-ffffffff812aa301: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812bab75)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812b6e60-ffffffff812b6e81: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812cb2b5)
Location: mm/memcontrol.c:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
Direct callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c7740-ffffffff812c7761: memcg_oom_recover.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
