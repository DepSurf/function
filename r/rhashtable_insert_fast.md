# Function: <code>rhashtable_insert_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff813bc01e)
Location: include/linux/rhashtable.h:674
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813d353b)
Location: include/linux/rhashtable.h:781
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813e651f)
Location: include/linux/rhashtable.h:825
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In ipc/util.c (ffffffff813a722b)
Location: include/linux/rhashtable.h:827
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d701)
Location: include/linux/rhashtable.h:827
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/act_api.c (ffffffff81882ada)
Location: include/linux/rhashtable.h:827
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
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
In ipc/util.c (ffffffff813d633a)
Location: include/linux/rhashtable.h:842
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef63)
Location: include/linux/rhashtable.h:842
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/act_api.c (ffffffff818d64ed)
Location: include/linux/rhashtable.h:842
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/ipv4/inet_fragment.c (ffffffff8193946d)
Location: include/linux/rhashtable.h:842
Inline: True
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
In kernel/bpf/offload.c (ffffffff811df7ce)
Location: include/linux/rhashtable.h:710
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f09ce)
Location: include/linux/rhashtable.h:710
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be79)
Location: include/linux/rhashtable.h:710
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/cls_api.c (ffffffff819018d6)
Location: include/linux/rhashtable.h:710
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff811f524d)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cf20)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81489524)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/cls_api.c (ffffffff8196296f)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff8120224d)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436d70)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a33ce)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81963e5b)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff81229999)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81487007)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814fe61b)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff81231529)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814a4627)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8151b87b)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff812356a9)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814aa5f6)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81521f7a)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff8126f849)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81502a2e)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81580148)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff812be254)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81593fc1)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8161f225)
Location: include/linux/rhashtable.h:819
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff81321eb4)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8163cb81)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff816d26c4)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff8135149d)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81675091)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8170b624)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffffffff8137892c)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff816b1451)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff817492c9)
Location: include/linux/rhashtable.h:828
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In kernel/bpf/offload.c (ffff800010289dc0)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d3ec)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff8000105990f8)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffff800010c08578)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (c04b9dd4)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d9800)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c074a3d8)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (c0d216a8)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (c000000000335c44)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c000000000666550)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c000000000710214)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (c000000000cf2ba8)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffe0001bde64)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384ccc)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5940)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffe0007863b8)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff811fa86d)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f350)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b9ae)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81903e2b)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff811ed5bd)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fdd0)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148c3ce)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff818bdc5b)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff811f863d)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b4f0)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81497a4e)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81954e5b)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
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
In kernel/bpf/offload.c (ffffffff81206d58)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81442452)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814afb9e)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81976e02)
Location: include/linux/rhashtable.h:826
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
</details>
</li>
</ul>

## Differences
