# Function: <code>init_srcu_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e39d0)
Location: kernel/rcu/srcu.c:135
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - mm/mmu_notifier.c:mmu_notifier_init
  - fs/notify/fsnotify.c:fsnotify_init
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff810e39d0-ffffffff810e3a98: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e9ce0)
Location: kernel/rcu/srcu.c:135
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - mm/mmu_notifier.c:mmu_notifier_init
  - fs/notify/fsnotify.c:fsnotify_init
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff810e9ce0-ffffffff810e9da8: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f0bb0)
Location: kernel/rcu/srcu.c:135
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - mm/mmu_notifier.c:mmu_notifier_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff810f0bb0-ffffffff810f0c78: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1430)
Location: kernel/rcu/srcutree.c:187
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff810f1430-ffffffff810f144c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb190)
Location: kernel/rcu/srcutree.c:188
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff810fb190-ffffffff810fb1ac: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81103620)
Location: kernel/rcu/srcutree.c:215
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81103620-ffffffff8110363c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110efd0)
Location: kernel/rcu/srcutree.c:221
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8110efd0-ffffffff8110efec: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811186e0)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff811186e0-ffffffff811186fc: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124ab0)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81124ab0-ffffffff81124acc: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811322a9)
Location: kernel/rcu/srcutree.c:223
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81132210-ffffffff8113222c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112da79)
Location: kernel/rcu/srcutree.c:212
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8112d9e0-ffffffff8112d9fc: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e0a9)
Location: kernel/rcu/srcutree.c:215
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8112e010-ffffffff8112e02c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f559)
Location: kernel/rcu/srcutree.c:207
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/notifier.c:srcu_init_notifier_head
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8114f4c0-ffffffff8114f4dc: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81176873)
Location: kernel/rcu/srcutree.c:295
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/notifier.c:srcu_init_notifier_head
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-core.c:blk_alloc_queue
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff811767c0-ffffffff811767e1: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae2b3)
Location: kernel/rcu/srcutree.c:295
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/notifier.c:srcu_init_notifier_head
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff811ae1f0-ffffffff811ae211: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c02a0)
Location: kernel/rcu/srcutree.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/notifier.c:srcu_init_notifier_head
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff811c02a0-ffffffff811c02ba: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0740)
Location: kernel/rcu/srcutree.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/notifier.c:srcu_init_notifier_head
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff811d0740-ffffffff811d075a: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800010189f88)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - virt/kvm/kvm_main.c:kvm_create_vm
  - virt/kvm/kvm_main.c:kvm_create_vm
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff800010189f88-ffff800010189fbc: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8a38)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c03d8a38-c03d8a5c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e48d0)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c0000000001e48d0-c0000000001e48f0: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f110)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe00011f110-ffffffe00011f140: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d090)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8111d090-ffffffff8111d0ac: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e150)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8110e150-ffffffff8110e16c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111af80)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8111af80-ffffffff8111af9c: init_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126860)
Location: kernel/rcu/srcutree.c:210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init
  - fs/notify/fsnotify.c:fsnotify_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81126860-ffffffff8112687c: init_srcu_struct (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
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
