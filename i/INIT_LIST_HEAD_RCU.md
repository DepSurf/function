# Function: <code>INIT_LIST_HEAD_RCU</code>

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
In security/smack/smackfs.c (ffffffff81365248)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8137f4f5)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In drivers/iommu/intel-svm.c (ffffffff8153c2d2)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In security/smack/smackfs.c (ffffffff8139b345)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813b8ce5)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In drivers/iommu/intel-svm.c (ffffffff81590e2d)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In security/smack/smackfs.c (ffffffff813b2035)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813d00a5)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In drivers/iommu/intel-svm.c (ffffffff815be6b5)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In kernel/bpf/core.c (ffffffff8118de98)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In security/smack/smackfs.c (ffffffff813c8635)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813e3938)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In drivers/iommu/intel-svm.c (ffffffff815d42d7)
Location: include/linux/rculist.h:30
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In kernel/trace/ftrace.c (ffffffff811678ab)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff8119c2af)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In security/smack/smackfs.c (ffffffff813eeac5)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8140a728)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b057)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In kernel/trace/ftrace.c (ffffffff811765ab)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811b13b3)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In security/smack/smackfs.c (ffffffff8141fb73)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8143bf38)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81454c4d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff816765f1)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In kernel/trace/ftrace.c (ffffffff811841fc)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811bfa4d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In security/smack/smackfs.c (ffffffff8143c643)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81458da8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81471f1d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff81695343)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
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
In kernel/trace/ftrace.c (ffffffff81190f9c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811d077f)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffff8146a1fb)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81486528)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149fb8d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff816ce0e5)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff8194f7ae)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffff8119cf9c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811dcd0f)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffff81483fdb)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814a03d8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ba13d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff816f1f34)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff8198614a)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffff811b2fac)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811f9722)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff8121f004)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In security/smack/smackfs.c (ffffffff814da12b)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814fa264)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8151a34d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa483)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In net/core/devlink.c (ffffffff81a5607d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb2e3e)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffffffff811b0b0c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811f8771)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff812227b2)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
```
```
In security/smack/smackfs.c (ffffffff814f76d8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81516fe4)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff815373cd)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff817b6975)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In net/core/devlink.c (ffffffff81a5d454)
Location: include/linux/rculist.h:31
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7274)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffffffff811b14c0)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811f958f)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff812276b6)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In security/smack/smackfs.c (ffffffff814fe308)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8151d894)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153fabd)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff81799c28)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In net/core/devlink.c (ffffffff81a3bd21)
Location: include/linux/rculist.h:31
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8e84)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffffffff811db350)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff8122ac26)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff8125f82f)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In security/smack/smackfs.c (ffffffff81559068)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8157b984)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159f0ad)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff81821854)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In net/core/devlink.c (ffffffff81af6102)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/mptcp/pm_netlink.c (ffffffff81c875d4)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffffffff812113b1)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff8126c57f)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff812a9f6d)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In security/smack/smackfs.c (ffffffff815f43c5)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81619f68)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81644a2d)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff8196193a)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff81c76260)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2eebf)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffffffff8125a921)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff812c15d4)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff813090d3)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In security/smack/smackfs.c (ffffffff816a4d65)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff816cd248)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fcecd)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca43b)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff81e2e9f4)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/mptcp/pm_netlink.c (ffffffff8200758f)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffffffff81271dc1)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_osnoise.c (ffffffff836da66a)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
```
```
In kernel/bpf/core.c (ffffffff812e83c5)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff8133802e)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In security/smack/smackfs.c (ffffffff816dd745)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81705958)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81736efd)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff81b1720a)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In net/devlink/core.c (ffffffff820420dd)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/mptcp/pm_netlink.c (ffffffff8208392f)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/cgroup/cgroup.c (ffffffff81236e5b)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/trace/ftrace.c (ffffffff8128c284)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_osnoise.c (ffffffff8390cbda)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
```
```
In kernel/bpf/core.c (ffffffff81306731)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/trampoline.c (ffffffff8135df5b)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In security/smack/smackfs.c (ffffffff81719625)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81743258)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff817779bd)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c757)
Location: include/linux/rculist.h:22
Inline: True
```
```
In net/devlink/core.c (ffffffff820feb83)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/mptcp/pm_netlink.c (ffffffff821590bf)
Location: include/linux/rculist.h:22
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
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
In kernel/trace/ftrace.c (ffff800010215e54)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffff80001025d700)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffff800010575e88)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (0)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In net/core/devlink.c (ffff800010c25598)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (c0454bcc)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (c0490f38)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (c0728808)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (c0747278)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (c0761be8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In net/core/devlink.c (c0d4122c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a11d8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_init
```
```
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0f84)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_table_alloc
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0650)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
```
```
In kernel/trace/ftrace.c (c000000000297a38)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (c000000000302100)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (c0000000006df598)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (c00000000070bb9c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (c000000000733b3c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab26bc)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_open
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_open
```
```
In net/core/devlink.c (c000000000d26314)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffe000175a4a)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffe00019bd24)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffe0003c8ce4)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffe0003e2e24)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f9d66)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In net/core/devlink.c (ffffffe00079f6a0)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffff811955bc)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811d532f)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffff8147c5bb)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814989b8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b271d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7724)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff81925fba)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffff811886cc)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811c80ef)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffff8146cfdb)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814893d8)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a313d)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff81695364)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff818dfd6a)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffff8119338c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811d30ff)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffff8147865b)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81494a58)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ae7ad)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5bf4)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff8197714a)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
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
In kernel/trace/ftrace.c (ffffffff811a0f5c)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/bpf/core.c (ffffffff811e13ef)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In security/smack/smackfs.c (ffffffff8149010b)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814aca78)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c71fd)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In drivers/iommu/intel-svm.c (ffffffff816ffec9)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In net/core/devlink.c (ffffffff8199963a)
Location: include/linux/rculist.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
</details>
</li>
</ul>

## Differences
