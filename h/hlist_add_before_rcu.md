# Function: <code>hlist_add_before_rcu</code>

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
In fs/notify/mark.c (ffffffff812507b4)
Location: include/linux/rculist.h:422
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff817a0327)
Location: include/linux/rculist.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff817d29bb)
Location: include/linux/rculist.h:422
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
In fs/notify/mark.c (ffffffff81278e3e)
Location: include/linux/rculist.h:544
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff8180df07)
Location: include/linux/rculist.h:544
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff818403ab)
Location: include/linux/rculist.h:544
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
In fs/notify/mark.c (ffffffff8128ca6e)
Location: include/linux/rculist.h:542
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff8183f35a)
Location: include/linux/rculist.h:542
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff8187202b)
Location: include/linux/rculist.h:542
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
In fs/notify/mark.c (ffffffff81299cb1)
Location: include/linux/rculist.h:543
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff818608fa)
Location: include/linux/rculist.h:543
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81896d99)
Location: include/linux/rculist.h:543
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
In fs/notify/mark.c (ffffffff812bd061)
Location: include/linux/rculist.h:544
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff818e097a)
Location: include/linux/rculist.h:544
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81918392)
Location: include/linux/rculist.h:544
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
In fs/notify/mark.c (ffffffff812e5cbe)
Location: include/linux/rculist.h:557
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff819370da)
Location: include/linux/rculist.h:557
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff8196fbb8)
Location: include/linux/rculist.h:557
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
In fs/notify/mark.c (ffffffff812fa8ad)
Location: include/linux/rculist.h:572
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81966aca)
Location: include/linux/rculist.h:572
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff819a57d8)
Location: include/linux/rculist.h:572
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
In fs/notify/mark.c (ffffffff8131aab2)
Location: include/linux/rculist.h:572
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff819ccb9a)
Location: include/linux/rculist.h:572
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81a11cf9)
Location: include/linux/rculist.h:572
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
In fs/notify/mark.c (ffffffff8132df99)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81a036fa)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81a48919)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (ffffffff81367664)
Location: include/linux/rculist.h:623
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81af2fac)
Location: include/linux/rculist.h:623
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81b3ecf1)
Location: include/linux/rculist.h:623
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
In fs/notify/mark.c (ffffffff813749c4)
Location: include/linux/rculist.h:652
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81affebc)
Location: include/linux/rculist.h:652
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81b4d701)
Location: include/linux/rculist.h:652
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
In fs/notify/mark.c (ffffffff8137b37a)
Location: include/linux/rculist.h:652
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81aeb39d)
Location: include/linux/rculist.h:652
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81b3bd2c)
Location: include/linux/rculist.h:652
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
In fs/notify/mark.c (ffffffff813c80b9)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffff81bab6ed)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81c025ac)
Location: include/linux/rculist.h:651
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
In fs/notify/mark.c (ffffffff8144f8dc)
Location: include/linux/rculist.h:651
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81d3e55d)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bb7d)
Location: include/linux/rculist.h:651
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
In fs/notify/mark.c (ffffffff814de17c)
Location: include/linux/rculist.h:651
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f0713d)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3df9f)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a7fd)
Location: include/linux/rculist.h:651
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
In fs/notify/mark.c (ffffffff815149af)
Location: include/linux/rculist.h:651
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f66bfd)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d89c)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrlabel.c (ffffffff81fca829)
Location: include/linux/rculist.h:651
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
In fs/notify/mark.c (ffffffff81548dce)
Location: include/linux/rculist.h:651
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8202d1cd)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_state.c (ffffffff8206abfc)
Location: include/linux/rculist.h:651
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrlabel.c (ffffffff82097fc9)
Location: include/linux/rculist.h:651
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
In fs/notify/mark.c (ffff8000103e99e8)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffff800010cbc184)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffff800010d0bd34)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (c05c11bc)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (c0dc79b8)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (c0e11a80)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (c0000000004f0bd0)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (c000000000dd5cd0)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (c000000000e36538)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (ffffffe00029e2b6)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In net/ipv4/fib_trie.c (ffffffe000812678)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffe000852ca4)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (ffffffff81326579)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff819a349a)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff819e7fa9)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (ffffffff81317119)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff8195cf5a)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff819a4d69)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (ffffffff81324049)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81a0dd3a)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81a52a29)
Location: include/linux/rculist.h:592
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
In fs/notify/mark.c (ffffffff81335d8c)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In net/ipv4/fib_trie.c (ffffffff81a1854a)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e9b9)
Location: include/linux/rculist.h:592
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
</ul>

## Differences
