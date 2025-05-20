# Function: <code>fib_notify_alias_delete</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af20d0)
Location: net/ipv4/fib_trie.c:1630
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81af20d0-ffffffff81af21c6: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81afeda0)
Location: net/ipv4/fib_trie.c:1630
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81afeda0-ffffffff81afee96: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aea700)
Location: net/ipv4/fib_trie.c:1667
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81aea700-ffffffff81aea807: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81ba9fd0)
Location: net/ipv4/fib_trie.c:1671
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81ba9fd0-ffffffff81baa0d7: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3cbd0)
Location: net/ipv4/fib_trie.c:1678
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81d3cbd0-ffffffff81d3cce6: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f05820)
Location: net/ipv4/fib_trie.c:1680
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81f05820-ffffffff81f05936: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f65270)
Location: net/ipv4/fib_trie.c:1680
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81f65270-ffffffff81f65384: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib_notify_alias_delete(struct net *net, u32 key, struct hlist_head *fah, struct fib_alias *fa_to_delete, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202b840)
Location: net/ipv4/fib_trie.c:1682
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8202b840-ffffffff8202b954: fib_notify_alias_delete (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
