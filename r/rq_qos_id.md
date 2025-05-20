# Function: <code>rq_qos_id</code>

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
In block/blk-sysfs.c (ffffffff814a07f2)
Location: block/blk-rq-qos.h:56
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff814cde44)
Location: block/blk-rq-qos.h:56
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_queue_depth
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff814cede4)
Location: block/blk-rq-qos.h:57
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff814fc6f5)
Location: block/blk-rq-qos.h:57
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_queue_depth
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff814e8154)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff81512141)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff8151a652)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff8154705f)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff8157332b)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff8157ada2)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
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
In block/blk-sysfs.c (ffffffff81562d4f)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff8158fcdf)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff81597e53)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
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
In block/blk-sysfs.c (ffffffff8156b4ff)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff81596a61)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff8159ec64)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
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
In block/blk-sysfs.c (ffffffff815cf77f)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff815fe081)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff816073d4)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
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
In block/blk-sysfs.c (ffffffff8167ade6)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-ioprio.c (ffffffff816ab6f2)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-ioprio.c:blk_ioprio_init
```
```
In block/blk-iocost.c (ffffffff816ae7dd)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff816baeee)
Location: block/blk-rq-qos.h:62
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
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
In block/blk-sysfs.c (ffffffff81737466)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In block/blk-iocost.c (ffffffff8176da43)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff8177b5ce)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_enable_default
  - block/blk-wbt.c:wbt_set_write_cache
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_disabled
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
In block/blk-sysfs.c (ffffffff81772e66)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In block/blk-rq-qos.c (ffffffff8179c84d)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_add
```
```
In block/blk-iocost.c (ffffffff817acf50)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff817b9d85)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_enable_default
  - block/blk-wbt.c:wbt_set_write_cache
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_disabled
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
In block/blk-sysfs.c (ffffffff817b51a6)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In block/blk-rq-qos.c (ffffffff817e02c0)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_add
```
```
In block/blk-iocost.c (ffffffff817f0d50)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff817fe4f5)
Location: block/blk-rq-qos.h:61
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_enable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_disabled
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
In block/blk-sysfs.c (ffff8000105e5f58)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffff8000106161c8)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffff800010622504)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (c0792cc4)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (c07c0014)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (c07ca0c4)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (c00000000077a268)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (c0000000007b569c)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (c0000000007c25e4)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffe000427192)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffe00044ccfe)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffe0004544f0)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff814e0734)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff8150a721)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff81512c32)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff814d10d4)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff814faba1)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff81502f52)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff814dc7c4)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff815067b1)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff8150ecc2)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-sysfs.c (ffffffff814f5634)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-iocost.c (ffffffff8151fa90)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_pd_init
```
```
In block/blk-wbt.c (ffffffff81528492)
Location: block/blk-rq-qos.h:60
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_get_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
</details>
</li>
</ul>

## Differences
