# Function: <code>rb_link_node_rcu</code>

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
In kernel/module.c (ffffffff81106952)
Location: include/linux/rbtree.h:89
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
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
In kernel/module.c (ffffffff8110e115)
Location: include/linux/rbtree.h:91
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
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
In kernel/module.c (ffffffff81115af5)
Location: include/linux/rbtree.h:91
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
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
In kernel/module.c (ffffffff81116a53)
Location: include/linux/rbtree.h:91
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8118f1b5)
Location: include/linux/rbtree.h:91
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff81122053)
Location: include/linux/rbtree.h:114
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8119d625)
Location: include/linux/rbtree.h:114
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff8112fb53)
Location: include/linux/rbtree.h:114
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811b1d61)
Location: include/linux/rbtree.h:114
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff8113b403)
Location: include/linux/rbtree.h:114
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c0611)
Location: include/linux/rbtree.h:114
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d194)
Location: include/linux/rbtree.h:114
Inline: True
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
In kernel/module.c (ffffffff81146a47)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d1124)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffff819d598f)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e659f)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffff81152627)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811dd6b4)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffff81a0c4ff)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1d58f)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffff81162677)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9fc2)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/ipv4/nexthop.c (ffffffff81afd5e5)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ea3b)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
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
In kernel/module.c (ffffffff8115e6d7)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f8ff2)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/ipv4/nexthop.c (ffffffff81b0b55c)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c61b)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
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
In kernel/module.c (ffffffff8115f727)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9dd2)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/ipv4/nexthop.c (ffffffff81af9145)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a337)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
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
In kernel/module.c (ffffffff81184ae7)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8122b4a2)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/ipv4/nexthop.c (ffffffff81bb9c97)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcd7aa)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
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
In kernel/module/tree_lookup.c (ffffffff81190c57)
Location: include/linux/rbtree.h:68
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126cef2)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/core/dev_addr_lists.c (ffffffff81c215b5)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_mod
```
```
In net/ipv4/nexthop.c (ffffffff81d4dc77)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d63790)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
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
In kernel/module/tree_lookup.c (ffffffff811ce217)
Location: include/linux/rbtree.h:68
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c2022)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/core/dev_addr_lists.c (ffffffff81dd3745)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_mod
```
```
In net/ipv4/nexthop.c (ffffffff81f175a7)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2e470)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
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
In kernel/module/tree_lookup.c (ffffffff811e2327)
Location: include/linux/rbtree.h:68
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e8ee2)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/core/dev_addr_lists.c (ffffffff81e44327)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_mod
```
```
In net/ipv4/nexthop.c (ffffffff81f77287)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8e03e)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
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
In kernel/module/tree_lookup.c (ffffffff811f80b7)
Location: include/linux/rbtree.h:68
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81307252)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In net/core/dev_addr_lists.c (ffffffff81f02f87)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_mod
```
```
In net/ipv4/nexthop.c (ffffffff8203da57)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205bdbe)
Location: include/linux/rbtree.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
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
In kernel/module.c (ffff8000101c123c)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffff80001025e2b0)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffff800010cc5b3c)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd9be4)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (c0408a08)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c0491974)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (c0dd1514)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (c0de38a0)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (c000000000227d1c)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c000000000302fe8)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (c000000000de2610)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (c000000000dfaaa8)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffe00014355c)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffe00019c7a4)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffe00081a724)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082a100)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffff8114ac47)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d5cd4)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffff819ac29f)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bcc1f)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffff8113def7)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c8a94)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffff81965d5f)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979a0f)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffff81148af7)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d3aa4)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffff81a16b3f)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2769f)
Location: include/linux/rbtree.h:78
Inline: True
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
In kernel/module.c (ffffffff81155777)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811e1d94)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In net/ipv4/nexthop.c (ffffffff81a2156f)
Location: include/linux/rbtree.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a32ccf)
Location: include/linux/rbtree.h:78
Inline: True
```
</details>
</li>
</ul>

## Differences
