# Function: <code>blkg_lookup_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d6f20)
Location: block/blk-cgroup.c:142
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_drain
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff813d6f20-ffffffff813d6f74: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141dec1)
Location: block/blk-cgroup.c:142
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:tg_conf_updated
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff8141cc10-ffffffff8141cc61: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81439481)
Location: block/blk-cgroup.c:142
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:tg_conf_updated
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff814381e0-ffffffff81438231: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81447a1f)
Location: block/blk-cgroup.c:143
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff81445a10-ffffffff81445a61: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8147461f)
Location: block/blk-cgroup.c:143
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-mq.c:blk_mq_bio_to_request
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff81472550-ffffffff814725a1: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a6ae0)
Location: block/blk-cgroup.c:143
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-mq.c:blk_mq_bio_to_request
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff814a6ae0-ffffffff814a6b31: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c0b10)
Location: block/blk-cgroup.c:166
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff814c0b10-ffffffff814c0b61: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814ef260)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff814ef260-ffffffff814ef2b1: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81508700)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81508700-ffffffff8150874e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156bf8c)
Location: block/blk-cgroup.c:197
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
**Symbols:**

```
ffffffff81569a10-ffffffff81569a5e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586c9a)
Location: block/blk-cgroup.c:203
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff815842c0-ffffffff8158430e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158d9c1)
Location: block/blk-cgroup.c:201
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8158b0c0-ffffffff8158b10e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f3431)
Location: block/blk-cgroup.c:204
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff815f00c0-ffffffff815f010e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a49f8)
Location: block/blk-cgroup.c:266
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
Direct callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff816a1130-ffffffff816a1192: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
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
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060b440)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffff80001060b440-ffff80001060b4b0: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b60d8)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
**Symbols:**

```
c07b60d8-c07b6134: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a7a90)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
c0000000007a7a90-c0000000007a7b3c: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe00044434a)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffe00044434a-ffffffe0004443a8: blkg_lookup_slowpath (STB_GLOBAL)
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
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81500ce0)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81500ce0-ffffffff81500d2e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f11f0)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff814f11f0-ffffffff814f123e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fcd70)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff814fcd70-ffffffff814fcdbe: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_slowpath(struct blkcg *blkcg, struct request_queue *q, bool update_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81515e20)
Location: block/blk-cgroup.c:194
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81515e20-ffffffff81515e6e: blkg_lookup_slowpath (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
