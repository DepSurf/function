# Function: <code>_raw_read_lock_irqsave</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818242a0)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - security/apparmor/label.c:vec_find
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - drivers/scsi/sg.c:sg_res_in_use
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff818242a0-ffffffff818242e0: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ef50)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_res_in_use
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff8189ef50-ffffffff8189ef90: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d4410)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_res_in_use
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff818d4410-ffffffff818d4450: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b600)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:vec_find
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff8190b600-ffffffff8190b640: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81995940)
Location: kernel/locking/spinlock.c:222
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:vec_find
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81995940-ffffffff8199597c: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1ed0)
Location: kernel/locking/spinlock.c:222
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff819f1ed0-ffffffff819f1f08: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d3f0)
Location: kernel/locking/spinlock.c:222
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81a2d3f0-ffffffff81a2d428: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d5c0)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81a9d5c0-ffffffff81a9d5ff: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4da0)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81ad4da0-ffffffff81ad4ddf: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccda0)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81bccda0-ffffffff81bccde3: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c458c0)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff81c458c0-ffffffff81c45903: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c38b80)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
**Symbols:**

```
ffffffff81c38b80-ffffffff81c38bc3: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d57460)
Location: kernel/locking/spinlock.c:234
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
**Symbols:**

```
ffffffff81d57460-ffffffff81d574a3: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29df0)
Location: kernel/locking/spinlock.c:234
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
**Symbols:**

```
ffffffff81f29df0-ffffffff81f29e06: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5d60)
Location: kernel/locking/spinlock.c:234
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
**Symbols:**

```
ffffffff820d5d60-ffffffff820d5d76: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82159140)
Location: kernel/locking/spinlock.c:234
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
**Symbols:**

```
ffffffff82159140-ffffffff82159156: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c9c0)
Location: kernel/locking/spinlock.c:234
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/eventpoll.c:ep_poll_callback
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
**Symbols:**

```
ffffffff8223c9c0-ffffffff8223c9d6: _raw_read_lock_irqsave (STB_GLOBAL)
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
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f658)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
c0e9f658-c0e9f69c: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000eea950)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
c000000000eea950-c000000000eeaa54: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c9494)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffe0008c9494-ffffffe0008c94cc: _raw_read_lock_irqsave (STB_GLOBAL)
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
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a73c10)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81a73c10-ffffffff81a73c4f: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2fde0)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81a2fde0-ffffffff81a2fe12: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ae0020)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81ae0020-ffffffff81ae005f: _raw_read_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int _raw_read_lock_irqsave(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec780)
Location: kernel/locking/spinlock.c:229
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
**Symbols:**

```
ffffffff81aec780-ffffffff81aec7c6: _raw_read_lock_irqsave (STB_GLOBAL)
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
