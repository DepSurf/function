# Function: <code>blkg_to_pd</code>

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
In block/blk-cgroup.c (ffffffff813d80a1)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff813d92dd)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_set_conf
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_drain
```
```
In block/cfq-iosched.c (ffffffff813dd6e1)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - block/cfq-iosched.c:__cfqg_set_weight_device
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff8141deff)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff81421d7c)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/cfq-iosched.c (ffffffff81425a09)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-cgroup.c (ffffffff814394bf)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8143cedc)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/cfq-iosched.c (ffffffff814447c9)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-cgroup.c (ffffffff81446c46)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8144c210)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/cfq-iosched.c (ffffffff81453cbb)
Location: include/linux/blk-cgroup.h:308
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-cgroup.c (ffffffff81473826)
Location: include/linux/blk-cgroup.h:304
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff81478919)
Location: include/linux/blk-cgroup.h:304
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/cfq-iosched.c (ffffffff8147d21b)
Location: include/linux/blk-cgroup.h:304
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-cgroup.c (ffffffff814a7856)
Location: include/linux/blk-cgroup.h:322
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff814acfd9)
Location: include/linux/blk-cgroup.h:322
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/cfq-iosched.c (ffffffff814b4189)
Location: include/linux/blk-cgroup.h:322
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_set_weight
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-cgroup.c (ffffffff814c19e3)
Location: include/linux/blk-cgroup.h:398
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff814c7369)
Location: include/linux/blk-cgroup.h:398
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
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
In block/blk-cgroup.c (ffffffff814f0033)
Location: include/linux/blk-cgroup.h:405
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff814f5bff)
Location: include/linux/blk-cgroup.h:405
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
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
In block/blk-cgroup.c (ffffffff815094e3)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8150f309)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff81511e1f)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup-rwstat.c (ffffffff8156c3f3)
Location: include/linux/blk-cgroup.h:385
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8157031d)
Location: include/linux/blk-cgroup.h:385
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_update_limit_valid
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff81573204)
Location: include/linux/blk-cgroup.h:385
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup-rwstat.c (ffffffff815871ba)
Location: include/linux/blk-cgroup.h:375
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8158ac95)
Location: include/linux/blk-cgroup.h:375
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff8158fb9b)
Location: include/linux/blk-cgroup.h:375
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup-rwstat.c (ffffffff8158e00a)
Location: include/linux/blk-cgroup.h:375
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8159177c)
Location: include/linux/blk-cgroup.h:375
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff8159667b)
Location: include/linux/blk-cgroup.h:375
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup-rwstat.c (ffffffff815f3b87)
Location: include/linux/blk-cgroup.h:380
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff815f89ac)
Location: include/linux/blk-cgroup.h:380
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_charge_bio_split
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-ioprio.c (ffffffff815f9334)
Location: include/linux/blk-cgroup.h:380
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_ioprio_track
```
```
In block/blk-iocost.c (ffffffff815fdc2f)
Location: include/linux/blk-cgroup.h:380
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-core.c (ffffffff81679466)
Location: block/blk-cgroup.h:289
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-cgroup-rwstat.c (ffffffff816a52ad)
Location: block/blk-cgroup.h:289
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff816aa9a8)
Location: block/blk-cgroup.h:289
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-ioprio.c (ffffffff816ab482)
Location: block/blk-cgroup.h:289
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_ioprio_track
```
```
In block/blk-iocost.c (ffffffff816b08a7)
Location: block/blk-cgroup.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-core.c (ffffffff81735937)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-cgroup-rwstat.c (ffffffff81764139)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff81769448)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-ioprio.c (ffffffff81769ff2)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_set_ioprio
```
```
In block/blk-iocost.c (ffffffff8177070f)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-core.c (ffffffff81771e99)
Location: block/blk-cgroup.h:274
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-cgroup-rwstat.c (ffffffff817a320b)
Location: block/blk-cgroup.h:274
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff817a8605)
Location: block/blk-cgroup.h:274
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-ioprio.c (ffffffff817a9042)
Location: block/blk-cgroup.h:274
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_set_ioprio
```
```
In block/blk-iocost.c (ffffffff817af758)
Location: block/blk-cgroup.h:274
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-core.c (ffffffff817b41bc)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6d5b)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff817ec375)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-ioprio.c (ffffffff817ece02)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_set_ioprio
```
```
In block/blk-iocost.c (ffffffff817f3568)
Location: block/blk-cgroup.h:273
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (ffff80001060c1d0)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffff800010612f60)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffff800010616018)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (c07b7384)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (c07bd8e8)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_update_limit_valid
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (c07bf8a8)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (c0000000007a9104)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (c0000000007b1540)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (c0000000007b4bb4)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (ffffffe000445196)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffe00044a462)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffe00044cbce)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (ffffffff81501ac3)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff815078e9)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff8150a3ff)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (ffffffff814f1fd3)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff814f7da9)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff814fa5ef)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (ffffffff814fdb53)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff81503979)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff8150648f)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-cgroup.c (ffffffff81517119)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8151cf2e)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
```
```
In block/blk-iocost.c (ffffffff8151ea2b)
Location: include/linux/blk-cgroup.h:407
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
</details>
</li>
</ul>

## Differences
