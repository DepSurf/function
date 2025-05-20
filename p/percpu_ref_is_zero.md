# Function: <code>percpu_ref_is_zero</code>

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
In block/blk-mq.c (ffffffff813c35b7)
Location: include/linux/percpu-refcount.h:319
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff813ff3a5)
Location: include/linux/percpu-refcount.h:319
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
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
In block/blk-mq.c (ffffffff81407087)
Location: include/linux/percpu-refcount.h:317
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff81446a85)
Location: include/linux/percpu-refcount.h:317
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
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
In block/blk-mq.c (ffffffff81421527)
Location: include/linux/percpu-refcount.h:317
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff81465149)
Location: include/linux/percpu-refcount.h:317
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
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
In block/blk-mq.c (ffffffff8142eef1)
Location: include/linux/percpu-refcount.h:318
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In lib/percpu-refcount.c (ffffffff8146a279)
Location: include/linux/percpu-refcount.h:318
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff81739962)
Location: include/linux/percpu-refcount.h:318
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In block/blk-mq.c (ffffffff8145a381)
Location: include/linux/percpu-refcount.h:319
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In lib/percpu-refcount.c (ffffffff81496569)
Location: include/linux/percpu-refcount.h:319
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff817ac104)
Location: include/linux/percpu-refcount.h:319
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In block/blk-mq.c (ffffffff8148d9fc)
Location: include/linux/percpu-refcount.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In lib/percpu-refcount.c (ffffffff814cb7c9)
Location: include/linux/percpu-refcount.h:325
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff817f7e44)
Location: include/linux/percpu-refcount.h:325
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In block/blk-mq.c (ffffffff814a728c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff814d5ebd)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff814e0550)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff81823ff4)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff811f736b)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff814d51cc)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff81501d13)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8150c4f0)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff81866494)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff8120432b)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff814ee4ac)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff8151fc40)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8152a340)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff818981d4)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff8122cd4f)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff8154e10f)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff81580bd0)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8158da60)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff81968394)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa6f0)
Location: lib/percpu-refcount.c:402
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff815aa190-ffffffff815aa1df: percpu_ref_is_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b5310)
Location: lib/percpu-refcount.c:408
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff815b4d90-ffffffff815b4ddf: percpu_ref_is_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8161b6b0)
Location: lib/percpu-refcount.c:408
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8161b050-ffffffff8161b09f: percpu_ref_is_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff816e8ec0)
Location: lib/percpu-refcount.c:409
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff816e87e0-ffffffff816e8843: percpu_ref_is_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff817d8f90)
Location: lib/percpu-refcount.c:410
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff817d87f0-ffffffff817d8853: percpu_ref_is_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff818181a0)
Location: lib/percpu-refcount.c:410
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff818179f0-ffffffff81817a53: percpu_ref_is_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8185d4a0)
Location: lib/percpu-refcount.c:410
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md.c:mddev_suspend
```
**Symbols:**

```
ffffffff8185ccd0-ffffffff8185cd33: percpu_ref_is_zero (STB_GLOBAL)
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
In kernel/bpf/cgroup.c (ffff80001028cb30)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffff8000105ed11c)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffff800010628950)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffff8000106356f8)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffff800010ae6858)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (c04bc220)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (c079961c)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (c07d007c)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (c07db568)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (c0bc5448)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (c000000000339090)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (c000000000782dd0)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (c0000000007ca49c)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (c0000000007dae88)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (c000000000bcce20)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffe0001c04ac)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffe00042cb06)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffe000459e1e)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffe000462ea8)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffe0006e0518)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff811fc94b)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff814e6a8c)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff81518220)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff81522920)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff8183e054)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff811ef69b)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff814d6ffc)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff81508530)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff81512c00)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff818056b4)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff811fa71b)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff814e2b1c)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff815142b0)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8151e9b0)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff8188d684)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
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
In kernel/bpf/cgroup.c (ffffffff812091db)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In block/blk-mq.c (ffffffff814fb996)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-pm.c (ffffffff8152da6b)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff81538270)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
```
In drivers/md/md.c (ffffffff818a3412)
Location: include/linux/percpu-refcount.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
