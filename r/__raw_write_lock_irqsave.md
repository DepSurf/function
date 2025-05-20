# Function: <code>__raw_write_lock_irqsave</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8182408a)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ed3a)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d41fa)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b38a)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8199590a)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1f15)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d435)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d4b5)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4c95)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccd65)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c45915)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c38bd5)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d574b5)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __raw_write_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8114ed10)
Location: include/linux/rwlock_api_smp.h:180
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
**Symbols:**

```
ffffffff8114ed10-ffffffff8114ed5f: __raw_write_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __raw_write_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8117df20)
Location: include/linux/rwlock_api_smp.h:180
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
**Symbols:**

```
ffffffff8117df20-ffffffff8117df84: __raw_write_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __raw_write_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8118ebc0)
Location: include/linux/rwlock_api_smp.h:180
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
**Symbols:**

```
ffffffff8118ebc0-ffffffff8118ec24: __raw_write_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __raw_write_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8119d570)
Location: include/linux/rwlock_api_smp.h:180
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
**Symbols:**

```
ffffffff8119d570-ffffffff8119d5d4: __raw_write_lock_irqsave (STB_LOCAL)
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
In arch/arm/xen/p2m.c (ffff8000100f0564)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
```
```
In security/apparmor/policy_ns.c (ffff8000105a10c4)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
```
```
In security/apparmor/label.c (ffff8000105a2b3c)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
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
```
```
In drivers/scsi/sg.c (ffff80001098f7a8)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1fc14)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
```
In drivers/leds/led-triggers.c (ffff800010b4a2d4)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f5b0)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000eeac38)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c94e2)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a73b05)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2fe25)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81adff15)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec9e5)
Location: include/linux/rwlock_api_smp.h:180
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
