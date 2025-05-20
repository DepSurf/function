# Function: <code>rb_replace_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813efe00)
Location: lib/rbtree.c:537
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - security/apparmor/label.c:__label_replace
```
**Symbols:**

```
ffffffff813efe00-ffffffff813efe64: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff814366d0)
Location: lib/rbtree.c:537
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - security/apparmor/label.c:__label_replace
```
**Symbols:**

```
ffffffff814366d0-ffffffff81436737: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff814536c0)
Location: lib/rbtree.c:552
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - security/apparmor/label.c:__label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff814536c0-ffffffff81453727: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f3930)
Location: lib/rbtree.c:554
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff818f3930-ffffffff818f3997: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819799e0)
Location: lib/rbtree.c:589
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/rbtree.c:rb_replace_node_cached
```
**Symbols:**

```
ffffffff819799e0-ffffffff81979a47: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d62a0)
Location: lib/rbtree.c:589
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/rbtree.c:rb_replace_node_cached
```
**Symbols:**

```
ffffffff819d62a0-ffffffff819d6300: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e4d0)
Location: lib/rbtree.c:589
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/rbtree.c:rb_replace_node_cached
```
**Symbols:**

```
ffffffff81a0e4d0-ffffffff81a0e530: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7d8f0)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff81a7d8f0-ffffffff81a7d950: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab4c20)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff81ab4c20-ffffffff81ab4c80: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815ef860)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff815ef860-ffffffff815ef8c3: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81613fc0)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81613fc0-ffffffff81614023: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7620)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - security/landlock/ruleset.c:insert_rule
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff815f7620-ffffffff815f7686: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81664db0)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - security/landlock/ruleset.c:insert_rule
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81664db0-ffffffff81664e16: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f250)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - security/landlock/ruleset.c:insert_rule
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff8177f250-ffffffff8177f2e7: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203bf20)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - fs/xattr.c:simple_xattr_set
  - security/apparmor/label.c:aa_label_replace
  - security/landlock/ruleset.c:insert_rule
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff8203bf20-ffffffff8203bfb7: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820ba490)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - fs/xattr.c:simple_xattr_set
  - security/apparmor/label.c:aa_label_replace
  - security/landlock/ruleset.c:insert_rule
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff820ba490-ffffffff820ba527: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82194da0)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
  - fs/xattr.c:simple_xattr_set
  - security/apparmor/label.c:aa_label_replace
  - security/landlock/ruleset.c:insert_rule
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff82194da0-ffffffff82194e37: rb_replace_node (STB_GLOBAL)
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
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f540)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffff800010d8f540-ffff800010d8f5b0: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e89cf8)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
c0e89cf8-c0e89d70: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed2170)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
c000000000ed2170-c000000000ed21f8: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7c44)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffe0008b7c44-ffffffe0008b7c90: rb_replace_node (STB_GLOBAL)
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
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53a70)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff81a53a70-ffffffff81a53ad0: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10b50)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff81a10b50-ffffffff81a10bb0: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81abfe60)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff81abfe60-ffffffff81abfec0: rb_replace_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node *victim, struct rb_node *new, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc330)
Location: lib/rbtree.c:553
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
  - security/apparmor/label.c:aa_label_replace
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
**Symbols:**

```
ffffffff81acc330-ffffffff81acc390: rb_replace_node (STB_GLOBAL)
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
