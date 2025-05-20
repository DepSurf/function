# Function: <code>cleanup_srcu_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e3b10)
Location: kernel/rcu/srcu.c:282
Inline: False
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/clk/clk.c:clk_notifier_unregister
```
**Symbols:**

```
ffffffff810e3b10-ffffffff810e3ba1: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e9e20)
Location: kernel/rcu/srcu.c:282
Inline: False
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/clk/clk.c:clk_notifier_unregister
```
**Symbols:**

```
ffffffff810e9e20-ffffffff810e9eb1: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f0cf0)
Location: kernel/rcu/srcu.c:282
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff810f0cf0-ffffffff810f0d86: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0d50)
Location: kernel/rcu/srcutree.c:348
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff810f0d50-ffffffff810f0e52: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fac00)
Location: kernel/rcu/srcutree.c:349
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff810fac00-ffffffff810fad01: cleanup_srcu_struct (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff8148e29c)
Location: include/linux/srcu.h:84
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In drivers/clk/clk.c (ffffffff815e0459)
Location: include/linux/srcu.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_notifier_unregister
```
```
In drivers/md/dm.c (ffffffff8180907e)
Location: include/linux/srcu.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
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
In block/blk-mq.c (ffffffff814a84bf)
Location: include/linux/srcu.h:84
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815fa3f9)
Location: include/linux/srcu.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_notifier_unregister
```
```
In drivers/md/dm.c (ffffffff818351cd)
Location: include/linux/srcu.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff811197f8-ffffffff81119874: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff81118110-ffffffff811181fe: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81125bd9-ffffffff81125c04: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff811244d0-ffffffff811245c4: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:383
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff811334eb-ffffffff81133516: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff81131c40-ffffffff81131d24: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81be2036-ffffffff81be2061: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff8112d420-ffffffff8112d504: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:375
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81bd40c6-ffffffff81bd40f1: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff8112da40-ffffffff8112db24: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:367
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81cae264-ffffffff81cae28f: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff8114ed20-ffffffff8114ee27: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81175e03)
Location: kernel/rcu/srcutree.c:594
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81e5e89d-ffffffff81e5e8b1: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff81175dc0-ffffffff81175f91: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ad6c0)
Location: kernel/rcu/srcutree.c:599
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff811ad510-ffffffff811ad6a3: cleanup_srcu_struct.part.0 (STB_LOCAL)
ffffffff82059ec5-ffffffff82059ed9: cleanup_srcu_struct.part.0.cold (STB_LOCAL)
ffffffff811ad6c0-ffffffff811ad719: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff820d86bc-ffffffff820d86d0: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff811bf6c0-ffffffff811bf88f: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:646
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - kernel/rcu/srcutree.c:srcu_module_notify
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff821b3986-ffffffff821b399a: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff811cfb30-ffffffff811cfcff: cleanup_srcu_struct (STB_GLOBAL)
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
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800010189a08)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
  - virt/kvm/kvm_main.c:kvm_create_vm
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffff800010189a08-ffff800010189b6c: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8494)
Location: kernel/rcu/srcutree.c:370
Inline: True
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c03d8494-c03d860c: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e3f60)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c0000000001e3f60-c0000000001e4114: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011eb6a)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffe00011eb6a-ffffffe00011ec7a: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_free_ns_head
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8111e1b9-ffffffff8111e1e4: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff8111cab0-ffffffff8111cba4: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_free_ns_head
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8110f225-ffffffff8110f250: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff8110db70-ffffffff8110dc64: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8111c0a9-ffffffff8111c0d4: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff8111a9a0-ffffffff8111aa94: cleanup_srcu_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cleanup_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:370
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff811277d7-ffffffff81127802: cleanup_srcu_struct.cold (STB_LOCAL)
ffffffff81126280-ffffffff81126374: cleanup_srcu_struct (STB_GLOBAL)
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
