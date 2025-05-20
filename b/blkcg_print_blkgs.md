# Function: <code>blkcg_print_blkgs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d8640)
Location: block/blk-cgroup.c:495
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:tg_print_max
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_weight_device
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
```
**Symbols:**

```
ffffffff813d8640-ffffffff813d871b: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141e380)
Location: block/blk-cgroup.c:495
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
```
**Symbols:**

```
ffffffff8141e380-ffffffff8141e454: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81439940)
Location: block/blk-cgroup.c:496
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
```
**Symbols:**

```
ffffffff81439940-ffffffff81439a14: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814470d0)
Location: block/blk-cgroup.c:497
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
```
**Symbols:**

```
ffffffff814470d0-ffffffff8144718c: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81473cb0)
Location: block/blk-cgroup.c:497
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
```
**Symbols:**

```
ffffffff81473cb0-ffffffff81473d6e: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a8190)
Location: block/blk-cgroup.c:508
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
```
**Symbols:**

```
ffffffff814a8190-ffffffff814a825d: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1d30)
Location: block/blk-cgroup.c:499
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
**Symbols:**

```
ffffffff814c1d30-ffffffff814c1e0f: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f0450)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
**Symbols:**

```
ffffffff814f0450-ffffffff814f053e: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815098f0)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff815098f0-ffffffff815099d8: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156a930)
Location: block/blk-cgroup.c:521
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff8156a930-ffffffff8156aa06: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81585380)
Location: block/blk-cgroup.c:502
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff81585380-ffffffff8158545b: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158bf30)
Location: block/blk-cgroup.c:500
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff8158bf30-ffffffff8158c00b: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f1720)
Location: block/blk-cgroup.c:515
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff815f1720-ffffffff815f181a: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a2770)
Location: block/blk-cgroup.c:576
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff816a2770-ffffffff816a2891: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8175fe80)
Location: block/blk-cgroup.c:585
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff8175fe80-ffffffff8175ff9b: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179ee50)
Location: block/blk-cgroup.c:675
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff8179ee50-ffffffff8179ef71: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e2930)
Location: block/blk-cgroup.c:688
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff817e2930-ffffffff817e2a4b: blkcg_print_blkgs (STB_GLOBAL)
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
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060c678)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffff80001060c678-ffff80001060c7f4: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b62f4)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
c07b62f4-c07b6404: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a95a0)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
c0000000007a95a0-c0000000007a9798: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe00044538a)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffe00044538a-ffffffe0004454a4: blkcg_print_blkgs (STB_GLOBAL)
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
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81501ed0)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff81501ed0-ffffffff81501fb8: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f23e0)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff814f23e0-ffffffff814f24c2: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fdf60)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff814fdf60-ffffffff814fe048: blkcg_print_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file *sf, struct blkcg *blkcg, u64 (*prfill)(struct seq_file *, struct blkg_policy_data *, int), const struct blkcg_policy *pol, int data, bool show_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815160a0)
Location: block/blk-cgroup.c:520
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
**Symbols:**

```
ffffffff815160a0-ffffffff81516184: blkcg_print_blkgs (STB_GLOBAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
