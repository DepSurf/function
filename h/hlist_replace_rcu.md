# Function: <code>hlist_replace_rcu</code>

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
In kernel/pid.c (ffffffff8109e6e1)
Location: include/linux/rculist.h:353
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8112ca21)
Location: include/linux/rculist.h:353
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff813402e6)
Location: include/linux/rculist.h:353
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a99f)
Location: include/linux/rculist.h:353
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff817a0a13)
Location: include/linux/rculist.h:353
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff817d2a36)
Location: include/linux/rculist.h:353
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810a1d81)
Location: include/linux/rculist.h:439
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81134c25)
Location: include/linux/rculist.h:439
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff81375986)
Location: include/linux/rculist.h:439
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff818085d1)
Location: include/linux/rculist.h:439
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff8180e671)
Location: include/linux/rculist.h:439
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff8184042a)
Location: include/linux/rculist.h:439
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810a6e41)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8113e9a5)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff8138c2b6)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff818396b1)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff8183fb0e)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff818720aa)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810a3d81)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81141c44)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff813a2006)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff8185ac07)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81860eb0)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81896e65)
Location: include/linux/rculist.h:437
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810aa371)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8114e9f4)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff813c7e06)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff818dab37)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff818e0f5a)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff819182ec)
Location: include/linux/rculist.h:438
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810b0f85)
Location: include/linux/rculist.h:451
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8115d2c8)
Location: include/linux/rculist.h:451
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff813f746a)
Location: include/linux/rculist.h:451
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81931ac8)
Location: include/linux/rculist.h:451
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81937ccc)
Location: include/linux/rculist.h:451
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff8196fb27)
Location: include/linux/rculist.h:451
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810ba0cb)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8116a0d8)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff81412f1a)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81961328)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff819676bc)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff819a5747)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810bffd9)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81176c58)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff814409aa)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5a4d)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff819cd902)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81a11cb0)
Location: include/linux/rculist.h:466
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810c63ab)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81182b88)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff8145a27a)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc5fd)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81a04452)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81a488d0)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810ce273)
Location: include/linux/rculist.h:496
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81196051)
Location: include/linux/rculist.h:496
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff814ad48e)
Location: include/linux/rculist.h:496
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb3bf)
Location: include/linux/rculist.h:496
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81af3870)
Location: include/linux/rculist.h:496
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81b3eca8)
Location: include/linux/rculist.h:496
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
In kernel/pid.c (ffffffff810c8d45)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81192de1)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff814ca98e)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81af82bf)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81b00780)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81b4d6b8)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
In kernel/pid.c (ffffffff810ca7e3)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81193e3c)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff814d0fbe)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae39df)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81aebe01)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81b3bce3)
Location: include/linux/rculist.h:525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810dd6f1)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff811bcceb)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff81529d0e)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba32ef)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81bac020)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81c02563)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810f7019)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff811f0bdb)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff815bf8ca)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35b06)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81d3ee7b)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bb34)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
In kernel/pid.c (ffffffff8111975b)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81235e1b)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff8166bc3a)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe0d6)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81f07a4a)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a7b4)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
In kernel/pid.c (ffffffff81126c39)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8124cc3b)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff816a43ae)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5db5a)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81f6751e)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81fca7e5)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
In kernel/pid.c (ffffffff81131219)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81266b3b)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff816e0e0e)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff8202411a)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff8202dafe)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff82097f85)
Location: include/linux/rculist.h:524
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
In kernel/pid.c (ffff800010124c04)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffff8000101f8eb0)
Location: include/linux/rculist.h:486
Inline: True
```
```
In security/selinux/avc.c (ffff8000105470c8)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In net/ipv4/fib_frontend.c (ffff800010cb49b8)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffff800010cbd010)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffff800010d0bcb4)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (c0377bb0)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (c0438498)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (c06fc3ec)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (c0dc03dc)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (c0dc895c)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (c0e11b2c)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (c00000000016e998)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (c00000000026f1b4)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (c00000000069d2c4)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (c000000000dcbaec)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (c000000000dd6f44)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (c000000000e364cc)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffe0000dcb92)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In security/selinux/avc.c (ffffffe0003a285a)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c5de)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffe0008133ca)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffe000852c70)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810c0729)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8117b1a8)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff8145285a)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c39d)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff819a41f2)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff819e7f60)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810aef2b)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff8116e348)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff814432aa)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81955e5d)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff8195dcb2)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff819a4d20)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810bfc7b)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81178f78)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff8144e8fa)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06c3d)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81a0ea92)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81a529e0)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/pid.c (ffffffff810c8089)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/pid.c:transfer_pid
```
```
In kernel/kprobes.c (ffffffff81186848)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In security/selinux/avc.c (ffffffff81465cda)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
```
```
In net/ipv4/fib_frontend.c (ffffffff81a112ed)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_unmerge
```
```
In net/ipv4/fib_trie.c (ffffffff81a192e2)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e970)
Location: include/linux/rculist.h:486
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
</ul>

## Differences
