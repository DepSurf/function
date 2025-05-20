# Function: <code>ioc_refresh_params</code>

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
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815105d0)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815105d0-ffffffff8151095d: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff81571bc0)
Location: block/blk-iocost.c:814
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81571bc0-ffffffff81571f4c: ioc_refresh_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff8158ce10)
Location: block/blk-iocost.c:901
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8158ce10-ffffffff8158d1db: ioc_refresh_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff81593b60)
Location: block/blk-iocost.c:901
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81593b60-ffffffff81593f29: ioc_refresh_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff815fafe0)
Location: block/blk-iocost.c:901
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815fafe0-ffffffff815fb3ee: ioc_refresh_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff816ae000)
Location: block/blk-iocost.c:900
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff816ae000-ffffffff816ae434: ioc_refresh_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff8176ccd0)
Location: block/blk-iocost.c:902
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8176ccd0-ffffffff8176d10f: ioc_refresh_params.isra.0 (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff817ad290)
Location: block/blk-iocost.c:951
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff817f1096)
Location: block/blk-iocost.c:951
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614020)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffff800010614020-ffff800010614370: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07beb14)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
c07beb14-c07bef60: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b3470)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
c0000000007b3470-c0000000007b38c4: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044b79e)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffe00044b79e-ffffffe00044ba4e: ioc_refresh_params (STB_LOCAL)
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
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508bb0)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81508bb0-ffffffff81508f3d: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9060)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff814f9060-ffffffff814f93ed: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504c40)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81504c40-ffffffff81504fcd: ioc_refresh_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc *ioc, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151e260)
Location: block/blk-iocost.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8151e260-ffffffff8151e5ed: ioc_refresh_params (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
