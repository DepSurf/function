# Function: <code>hlist_add_behind_rcu</code>

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
In fs/namespace.c (ffffffff8122cda2)
Location: include/linux/rculist.h:449
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
```
```
In fs/notify/mark.c (ffffffff81250788)
Location: include/linux/rculist.h:449
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff817a03d9)
Location: include/linux/rculist.h:449
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff817d2ade)
Location: include/linux/rculist.h:449
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
In fs/namespace.c (ffffffff81256ea3)
Location: include/linux/rculist.h:571
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
```
```
In fs/notify/mark.c (ffffffff81278e0e)
Location: include/linux/rculist.h:571
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff8180dfb9)
Location: include/linux/rculist.h:571
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff818404e2)
Location: include/linux/rculist.h:571
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
In fs/notify/mark.c (ffffffff8128ca3e)
Location: include/linux/rculist.h:569
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff8183f413)
Location: include/linux/rculist.h:569
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81850a7a)
Location: include/linux/rculist.h:569
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff81872162)
Location: include/linux/rculist.h:569
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
In fs/notify/mark.c (ffffffff81299d31)
Location: include/linux/rculist.h:570
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff8186099f)
Location: include/linux/rculist.h:570
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff818745ff)
Location: include/linux/rculist.h:570
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff81896eb6)
Location: include/linux/rculist.h:570
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
In fs/notify/mark.c (ffffffff812bd0e1)
Location: include/linux/rculist.h:571
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff818e0a1f)
Location: include/linux/rculist.h:571
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f4b69)
Location: include/linux/rculist.h:571
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff819183ea)
Location: include/linux/rculist.h:571
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
In fs/notify/mark.c (ffffffff812e5da0)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81937194)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194b280)
Location: include/linux/rculist.h:584
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff8196fc51)
Location: include/linux/rculist.h:584
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
In fs/notify/mark.c (ffffffff812fa992)
Location: include/linux/rculist.h:599
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81966b84)
Location: include/linux/rculist.h:599
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c09d)
Location: include/linux/rculist.h:599
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff819a5871)
Location: include/linux/rculist.h:599
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
In fs/notify/mark.c (ffffffff8131ab1f)
Location: include/linux/rculist.h:599
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff819ccc25)
Location: include/linux/rculist.h:599
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e59e4)
Location: include/linux/rculist.h:599
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff81a11dd5)
Location: include/linux/rculist.h:599
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
In fs/notify/mark.c (ffffffff8132e039)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81a0379d)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c9df)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff81a489f5)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (ffffffff813676f8)
Location: include/linux/rculist.h:650
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81af3036)
Location: include/linux/rculist.h:650
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ffac)
Location: include/linux/rculist.h:650
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81b3ed23)
Location: include/linux/rculist.h:650
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
In fs/notify/mark.c (ffffffff81374a58)
Location: include/linux/rculist.h:679
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81afff46)
Location: include/linux/rculist.h:679
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1e29c)
Location: include/linux/rculist.h:679
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81b4d733)
Location: include/linux/rculist.h:679
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
In fs/notify/mark.c (ffffffff8137b40f)
Location: include/linux/rculist.h:679
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81aeb440)
Location: include/linux/rculist.h:679
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0bbfe)
Location: include/linux/rculist.h:679
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81b3bdf6)
Location: include/linux/rculist.h:679
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
In fs/notify/mark.c (ffffffff813c8155)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81bab790)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcebbe)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81c02676)
Location: include/linux/rculist.h:678
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
In fs/notify/mark.c (ffffffff8144f948)
Location: include/linux/rculist.h:678
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81d3e5ef)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d65aee)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bbc1)
Location: include/linux/rculist.h:678
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
In kernel/printk/printk.c (ffffffff81190785)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
```
```
In fs/notify/mark.c (ffffffff814de1e8)
Location: include/linux/rculist.h:678
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f071cf)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f30a88)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a841)
Location: include/linux/rculist.h:678
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
In kernel/printk/printk.c (ffffffff811a209f)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
```
```
In fs/notify/mark.c (ffffffff81514a1b)
Location: include/linux/rculist.h:678
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f66c96)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f90af8)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff81fca86d)
Location: include/linux/rculist.h:678
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
In kernel/printk/printk.c (ffffffff811b2f70)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
```
```
In fs/notify/mark.c (ffffffff81548e31)
Location: include/linux/rculist.h:678
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8202d269)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205e868)
Location: include/linux/rculist.h:678
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_inexact_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/ipv6/addrlabel.c (ffffffff8209800d)
Location: include/linux/rculist.h:678
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
In fs/notify/mark.c (ffff8000103e9b0c)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffff800010cbc250)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8d88)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffff800010d0bdf8)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (c05c12f8)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (c0dc7a90)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (c0de29a4)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (c0e11b70)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (c0000000004f0e04)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (c000000000dd5dd0)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (c000000000df953c)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/ipv6/addrlabel.c (c000000000e366c8)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (ffffffe00029e3e4)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffe00081272a)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffe0008292c4)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffe000852d8c)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (ffffffff81326619)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff819a353d)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bc06f)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff819e8085)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (ffffffff813171b9)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff8195cffd)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978e5f)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff819a4e45)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (ffffffff813240e9)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81a0dddd)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26aef)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff81a52b05)
Location: include/linux/rculist.h:619
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
In fs/notify/mark.c (ffffffff81335e27)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81a185ed)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31f8f)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert_list
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/ipv6/addrlabel.c (ffffffff81a5ea77)
Location: include/linux/rculist.h:619
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
</ul>

## Differences
