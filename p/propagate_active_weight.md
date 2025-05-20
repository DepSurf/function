# Function: <code>propagate_active_weight</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510980)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff81510980-ffffffff815109a7: propagate_active_weight (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff81572401)
Location: block/blk-iocost.c:949
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614890)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffff800010614890-ffff8000106148f4: propagate_active_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bf5ac)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
c07bf5ac-c07bf5e0: propagate_active_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b3900)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
c0000000007b3900-c0000000007b3964: propagate_active_weight (STB_LOCAL)
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
In block/blk-iocost.c (ffffffe00044c958)
Location: block/blk-iocost.c:951
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508f60)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff81508f60-ffffffff81508f87: propagate_active_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9410)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff814f9410-ffffffff814f9437: propagate_active_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504ff0)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff81504ff0-ffffffff81505017: propagate_active_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq *iocg, u32 active, u32 inuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151e650)
Location: block/blk-iocost.c:951
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:weight_updated
```
**Symbols:**

```
ffffffff8151e650-ffffffff8151e677: propagate_active_weight (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
