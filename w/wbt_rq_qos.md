# Function: <code>wbt_rq_qos</code>

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
In block/blk-sysfs.c (ffffffff814a07ee)
Location: block/blk-rq-qos.h:67
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff814cde44)
Location: block/blk-rq-qos.h:67
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
In block/blk-sysfs.c (ffffffff814ceddf)
Location: block/blk-rq-qos.h:68
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff814fc6f5)
Location: block/blk-rq-qos.h:68
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
In block/blk-sysfs.c (ffffffff814e814f)
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff8151a652)
Location: block/blk-rq-qos.h:71
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
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff8157ada2)
Location: block/blk-rq-qos.h:71
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
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff81597e53)
Location: block/blk-rq-qos.h:71
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
Location: block/blk-rq-qos.h:72
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff8159ec64)
Location: block/blk-rq-qos.h:72
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
Location: block/blk-rq-qos.h:73
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff816073d4)
Location: block/blk-rq-qos.h:73
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
Location: block/blk-rq-qos.h:73
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff816bafc3)
Location: block/blk-rq-qos.h:73
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81737466)
Location: block/blk-rq-qos.h:72
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In block/blk-wbt.c (ffffffff8177a055)
Location: block/blk-rq-qos.h:72
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81772e66)
Location: block/blk-rq-qos.h:72
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In block/blk-wbt.c (ffffffff817b9d85)
Location: block/blk-rq-qos.h:72
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
Location: block/blk-rq-qos.h:72
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In block/blk-wbt.c (ffffffff817fe4f5)
Location: block/blk-rq-qos.h:72
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
In block/blk-sysfs.c (ffff8000105e5f54)
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffff800010622504)
Location: block/blk-rq-qos.h:71
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
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (c07ca0c4)
Location: block/blk-rq-qos.h:71
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
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (c0000000007c25e4)
Location: block/blk-rq-qos.h:71
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
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffe0004544f0)
Location: block/blk-rq-qos.h:71
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
In block/blk-sysfs.c (ffffffff814e072f)
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff81512c32)
Location: block/blk-rq-qos.h:71
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
In block/blk-sysfs.c (ffffffff814d10cf)
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff81502f52)
Location: block/blk-rq-qos.h:71
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
In block/blk-sysfs.c (ffffffff814dc7bf)
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff8150ecc2)
Location: block/blk-rq-qos.h:71
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
In block/blk-sysfs.c (ffffffff814f562f)
Location: block/blk-rq-qos.h:71
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-wbt.c (ffffffff81528492)
Location: block/blk-rq-qos.h:71
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
