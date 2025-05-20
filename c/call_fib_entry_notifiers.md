# Function: <code>call_fib_entry_notifiers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_info *fi, u8 tos, u8 type, u32 tb_id, u32 nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183d650)
Location: net/ipv4/fib_trie.c:197
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8183d650-ffffffff8183d6cf: call_fib_entry_notifiers (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffffffff818617fa)
Location: net/ipv4/fib_trie.c:103
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e18fb)
Location: net/ipv4/fib_trie.c:103
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81935de0)
Location: net/ipv4/fib_trie.c:104
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81935de0-ffffffff81935e59: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819657e0)
Location: net/ipv4/fib_trie.c:104
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff819657e0-ffffffff81965859: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cb790)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff819cb790-ffffffff819cb809: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a022e0)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81a022e0-ffffffff81a02359: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af2058)
Location: net/ipv4/fib_trie.c:91
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:__fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81afee49)
Location: net/ipv4/fib_trie.c:91
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aea7b0)
Location: net/ipv4/fib_trie.c:91
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81baa080)
Location: net/ipv4/fib_trie.c:91
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3cc9d)
Location: net/ipv4/fib_trie.c:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f058ed)
Location: net/ipv4/fib_trie.c:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f6533b)
Location: net/ipv4/fib_trie.c:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202b90b)
Location: net/ipv4/fib_trie.c:93
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
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
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbabf0)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffff800010cbabf0-ffff800010cbac98: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc6510)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
c0dc6510-c0dc65a4: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd41e0)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
c000000000dd41e0-c000000000dd4278: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe00081144e)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffe00081144e-ffffffe0008114c8: call_fib_entry_notifiers (STB_LOCAL)
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
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a2080)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff819a2080-ffffffff819a20f9: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195bb40)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8195bb40-ffffffff8195bbb9: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0c920)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81a0c920-ffffffff81a0c999: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net *net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias *fa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a170f0)
Location: net/ipv4/fib_trie.c:92
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81a170f0-ffffffff81a17169: call_fib_entry_notifiers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
