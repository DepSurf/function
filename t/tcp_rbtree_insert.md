# Function: <code>tcp_rbtree_insert</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818090e6)
Location: net/ipv4/tcp_input.c:4775
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
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
In net/ipv4/tcp_input.c (ffffffff81829395)
Location: net/ipv4/tcp_input.c:4735
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ae050)
Location: net/ipv4/tcp_input.c:4694
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff818ae050-ffffffff818ae0a3: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81903700)
Location: net/ipv4/tcp_input.c:4803
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81903700-ffffffff81903753: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819318a0)
Location: net/ipv4/tcp_input.c:4827
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff819318a0-ffffffff819318f3: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81994fa0)
Location: net/ipv4/tcp_input.c:4834
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81994fa0-ffffffff81994ff9: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cbaf0)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff819cbaf0-ffffffff819cbb49: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab217a)
Location: net/ipv4/tcp_input.c:4926
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81ab9a40-ffffffff81ab9a99: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abd143)
Location: net/ipv4/tcp_input.c:5065
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81ac4e40-ffffffff81ac4e99: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa7f90)
Location: net/ipv4/tcp_input.c:5073
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81aaff30-ffffffff81aaff89: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b64398)
Location: net/ipv4/tcp_input.c:5107
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81b6cd10-ffffffff81b6cd69: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf31b8)
Location: net/ipv4/tcp_input.c:5137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81cfb8a0-ffffffff81cfb90a: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb77e8)
Location: net/ipv4/tcp_input.c:5150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81ec03f0-ffffffff81ec045a: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f15f15)
Location: net/ipv4/tcp_input.c:5155
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81f1e960-ffffffff81f1e9ca: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fda324)
Location: net/ipv4/tcp_input.c:5293
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81fe2ff0-ffffffff81fe305a: tcp_rbtree_insert (STB_GLOBAL)
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
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7e728)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffff800010c7e728-ffff800010c7e79c: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8d720)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
c0d8d720-c0d8d798: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d88a10)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
c000000000d88a10-c000000000d88aa8: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e0a98)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffe0007e0a98-ffffffe0007e0afa: tcp_rbtree_insert (STB_GLOBAL)
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
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196b960)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff8196b960-ffffffff8196b9b9: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81925450)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff81925450-ffffffff819254a9: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d6130)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff819d6130-ffffffff819d6189: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root *root, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dfd50)
Location: net/ipv4/tcp_input.c:4885
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
**Symbols:**

```
ffffffff819dfd50-ffffffff819dfda9: tcp_rbtree_insert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
