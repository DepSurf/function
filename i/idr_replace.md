# Function: <code>idr_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *idr_replace(struct idr *idp, void *ptr, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813e9ea0)
Location: lib/idr.c:793
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_idr_replace
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813e9ea0-ffffffff813e9f44: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *idr_replace(struct idr *idp, void *ptr, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430280)
Location: lib/idr.c:793
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_idr_replace
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81430280-ffffffff81430320: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *idr_replace(struct idr *idp, void *ptr, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c4b0)
Location: lib/idr.c:793
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_idr_replace
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8144c4b0-ffffffff8144c553: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ecb90)
Location: lib/idr.c:151
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818ecb90-ffffffff818ecc4b: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81972c50)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81972c50-ffffffff81972c6a: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf190)
Location: lib/idr.c:292
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - security/apparmor/secid.c:aa_secid_update
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff819cf190-ffffffff819cf24a: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a08600)
Location: lib/idr.c:288
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81a08600-ffffffff81a086a0: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77fb0)
Location: lib/idr.c:299
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81a77fb0-ffffffff81a78052: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf380)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81aaf380-ffffffff81aaf422: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e90a0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/vmscan.c:register_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_secid_update
  - block/genhd.c:del_gendisk
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_add_char_device
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff815e90a0-ffffffff815e9142: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160e150)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/vmscan.c:register_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_secid_update
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_add_char_device
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff8160e150-ffffffff8160e1f2: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f18a0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_secid_update
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff815f18a0-ffffffff815f1942: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165ea10)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:mem_cgroup_alloc
  - security/apparmor/secid.c:aa_secid_update
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff8165ea10-ffffffff8165eab2: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff817782b0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff817782b0-ffffffff81778364: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82021030)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff82021030-ffffffff820210e4: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a1050)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
  - net/sched/act_api.c:tcf_idr_check_alloc
```
**Symbols:**

```
ffffffff820a1050-ffffffff820a1104: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82179030)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:mem_cgroup_css_online
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/gpu/drm/drm_auth.c:drm_authmagic
  - drivers/gpu/drm/drm_drv.c:drm_minor_unregister
  - drivers/gpu/drm/drm_drv.c:drm_minor_register
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_delete
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_object_register
  - drivers/accel/drm_accel.c:accel_minor_replace
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_insert_many
```
**Symbols:**

```
ffffffff82179030-ffffffff821790e4: idr_replace (STB_GLOBAL)
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
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88c00)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffff800010d88c00-ffff800010d88cb4: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83b1c)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
c0e83b1c-c0e83bd8: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec95a0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
c000000000ec95a0-c000000000ec9684: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2a98)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffe0008b2a98-ffffffe0008b2b0c: idr_replace (STB_GLOBAL)
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
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4e1d0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81a4e1d0-ffffffff81a4e272: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b2c0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81a0b2c0-ffffffff81a0b362: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba5c0)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81aba5c0-ffffffff81aba662: idr_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *idr_replace(struct idr *idr, void *ptr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac6a10)
Location: lib/idr.c:290
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - mm/vmscan.c:register_shrinker_prepared
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_insert
```
**Symbols:**

```
ffffffff81ac6a10-ffffffff81ac6ab2: idr_replace (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct idr *idr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr *idp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int id</code> ➡️ <code>long unsigned int id</code>
</li>
</ul>
</details>
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
