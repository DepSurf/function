# Function: <code>_raw_write_unlock_irqrestore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81823f40)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_remove
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - drivers/iommu/amd_iommu.c:protection_domain_free
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81823f40-ffffffff81823f58: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ebf0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - security/apparmor/policy_ns.c:destroy_ns
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:protection_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff8189ebf0-ffffffff8189ec08: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d40b0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - security/apparmor/policy_ns.c:destroy_ns
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:domain_id_free
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff818d40b0-ffffffff818d40c8: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b240)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:domain_id_free
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff8190b240-ffffffff8190b258: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819955e0)
Location: kernel/locking/spinlock.c:326
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:domain_id_free
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff819955e0-ffffffff819955f8: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1be0)
Location: kernel/locking/spinlock.c:326
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff819f1be0-ffffffff819f1bf8: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d1a0)
Location: kernel/locking/spinlock.c:326
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81a2d1a0-ffffffff81a2d1b8: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d290)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81a9d290-ffffffff81a9d2ab: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4a70)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81ad4a70-ffffffff81ad4a8b: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccbf0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81bccbf0-ffffffff81bccc0b: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c457b0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81c457b0-ffffffff81c457cb: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c38aa0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81c38aa0-ffffffff81c38abe: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d57380)
Location: kernel/locking/spinlock.c:338
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81d57380-ffffffff81d5739e: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29d50)
Location: kernel/locking/spinlock.c:348
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff81f29d50-ffffffff81f29d90: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5c80)
Location: kernel/locking/spinlock.c:348
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff820d5c80-ffffffff820d5cc8: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82159060)
Location: kernel/locking/spinlock.c:348
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff82159060-ffffffff821590a8: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c8e0)
Location: kernel/locking/spinlock.c:348
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff8223c8e0-ffffffff8223c928: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f0ac)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - sound/core/control.c:snd_ctl_release
```
**Symbols:**

```
c0e9f0ac-c0e9f0dc: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000eea110)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
c000000000eea110-c000000000eea158: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c95ae)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffe0008c95ae-ffffffe0008c95e2: _raw_write_unlock_irqrestore (STB_GLOBAL)
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
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a738e0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81a738e0-ffffffff81a738fb: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2fc50)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81a2fc50-ffffffff81a2fc60: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81adfcf0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81adfcf0-ffffffff81adfd0b: _raw_write_unlock_irqrestore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _raw_write_unlock_irqrestore(rwlock_t *lock, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec6a0)
Location: kernel/locking/spinlock.c:333
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81aec6a0-ffffffff81aec6cb: _raw_write_unlock_irqrestore (STB_GLOBAL)
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
