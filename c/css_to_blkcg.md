# Function: <code>css_to_blkcg</code>

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
In mm/backing-dev.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-cgroup.c (ffffffff813d7c99)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/cfq-iosched.c (ffffffff813de699)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
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
In mm/backing-dev.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8141d99d)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8142483b)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
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
In mm/backing-dev.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81438f5d)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/cfq-iosched.c (ffffffff81440248)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
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
In mm/backing-dev.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814479fc)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (0)
Location: include/linux/blk-cgroup.h:221
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8144f4cd)
Location: include/linux/blk-cgroup.h:221
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
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
In mm/backing-dev.c (0)
Location: include/linux/blk-cgroup.h:223
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:223
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk-cgroup.h:223
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814745fc)
Location: include/linux/blk-cgroup.h:223
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (0)
Location: include/linux/blk-cgroup.h:223
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8147b60d)
Location: include/linux/blk-cgroup.h:223
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
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
In mm/backing-dev.c (ffffffff81218d27)
Location: include/linux/blk-cgroup.h:224
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In block/blk-core.c (ffffffff81482960)
Location: include/linux/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148eb54)
Location: include/linux/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/blk-cgroup.c (ffffffff814a8975)
Location: include/linux/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814ad020)
Location: include/linux/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff814b2767)
Location: include/linux/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
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
In mm/backing-dev.c (ffffffff8122bb77)
Location: include/linux/blk-cgroup.h:250
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814982fa)
Location: include/linux/blk-cgroup.h:250
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff814c3389)
Location: include/linux/blk-cgroup.h:250
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814c73b0)
Location: include/linux/blk-cgroup.h:250
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
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
In mm/backing-dev.c (ffffffff8123b854)
Location: include/linux/blk-cgroup.h:257
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814c617a)
Location: include/linux/blk-cgroup.h:257
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff814f1a79)
Location: include/linux/blk-cgroup.h:257
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f5bd5)
Location: include/linux/blk-cgroup.h:257
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
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
In mm/backing-dev.c (ffffffff81249cec)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814de57a)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff8150b060)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150f34e)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81510437)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff81277f10)
Location: include/linux/blk-cgroup.h:237
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff8153ea9b)
Location: include/linux/blk-cgroup.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
```
In block/blk-cgroup.c (ffffffff8156bfc3)
Location: include/linux/blk-cgroup.h:237
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_rstat_flush
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8156c3af)
Location: include/linux/blk-cgroup.h:237
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8156ee49)
Location: include/linux/blk-cgroup.h:237
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
```
In block/blk-iocost.c (ffffffff81571757)
Location: include/linux/blk-cgroup.h:237
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff81282690)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff81586cd8)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_rstat_flush
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff81587176)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff81589bfe)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8158c817)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff812877a0)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff8158da18)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8158dfc6)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff815905fe)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81593557)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff812c6f00)
Location: include/linux/blk-cgroup.h:232
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff815f3488)
Location: include/linux/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_online
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff815f3b35)
Location: include/linux/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff815f75a0)
Location: include/linux/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-ioprio.c (ffffffff815f9433)
Location: include/linux/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - block/blk-ioprio.c:ioprio_show_prio_policy
```
```
In block/blk-iocost.c (ffffffff815fa6e7)
Location: include/linux/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.h:108
Inline: True
```
```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup.h:108
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: block/blk-cgroup.h:108
Inline: True
```
```
In block/blk-throttle.c (0)
Location: block/blk-cgroup.h:108
Inline: True
```
```
In block/blk-ioprio.c (0)
Location: block/blk-cgroup.h:108
Inline: True
```
```
In block/blk-iocost.c (0)
Location: block/blk-cgroup.h:108
Inline: True
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
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.h:118
Inline: True
```
```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup.h:118
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: block/blk-cgroup.h:118
Inline: True
```
```
In block/blk-throttle.c (0)
Location: block/blk-cgroup.h:118
Inline: True
```
```
In block/blk-ioprio.c (0)
Location: block/blk-cgroup.h:118
Inline: True
```
```
In block/blk-iocost.c (0)
Location: block/blk-cgroup.h:118
Inline: True
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
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-throttle.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-ioprio.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-iocost.c (0)
Location: block/blk-cgroup.h:119
Inline: True
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
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-cgroup-fc-appid.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-throttle.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-ioprio.c (0)
Location: block/blk-cgroup.h:119
Inline: True
```
```
In block/blk-iocost.c (0)
Location: block/blk-cgroup.h:119
Inline: True
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
In mm/backing-dev.c (ffff8000102df470)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffff8000105db9c0)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffff80001060e9b8)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff800010612f20)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffff800010613bf0)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (c05042f4)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (c0788570)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (c07b9228)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07bd89c)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
```
In block/blk-iocost.c (c07bf428)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (c00000000039efe0)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (c00000000076b934)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (c0000000007abf98)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007b157c)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c0000000007b2f30)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (0)
Location: include/linux/blk-cgroup.h:259
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/blk-cgroup.h:259
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000446e28)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (0)
Location: include/linux/blk-cgroup.h:259
Inline: True
```
```
In block/blk-iocost.c (ffffffe00044ca34)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff8124233c)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814d6b5a)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff81503640)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150792e)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81508a17)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff8123530c)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814c751a)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff814f3b00)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f7dee)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff814f8ec7)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff812400dc)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814d2bea)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff814ff6d0)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815039be)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81504aa7)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
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
In mm/backing-dev.c (ffffffff8124f82d)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/bio.c (ffffffff814eb774)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg_from_css
```
```
In block/blk-cgroup.c (ffffffff81518868)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8151cf73)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8151e0c7)
Location: include/linux/blk-cgroup.h:259
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
```
</details>
</li>
</ul>

## Differences
