# Function: <code>mptcp_join_entry_hash</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff81bc94f4)
Location: net/mptcp/syncookies.c:38
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 mptcp_join_entry_hash(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff81bbcc60)
Location: net/mptcp/syncookies.c:38
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff81bbcc60-ffffffff81bbcd76: mptcp_join_entry_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 mptcp_join_entry_hash(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff81c8cac0)
Location: net/mptcp/syncookies.c:38
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff81c8cac0-ffffffff81c8cbd6: mptcp_join_entry_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 mptcp_join_entry_hash(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff81e36170)
Location: net/mptcp/syncookies.c:38
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff81e36170-ffffffff81e3629a: mptcp_join_entry_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 mptcp_join_entry_hash(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff8200f140)
Location: net/mptcp/syncookies.c:38
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff8200f140-ffffffff8200f26a: mptcp_join_entry_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 mptcp_join_entry_hash(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff8208bd30)
Location: net/mptcp/syncookies.c:38
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff8208bd30-ffffffff8208be5a: mptcp_join_entry_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 mptcp_join_entry_hash(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/syncookies.c (ffffffff821621f0)
Location: net/mptcp/syncookies.c:38
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff821621f0-ffffffff8216231a: mptcp_join_entry_hash (STB_LOCAL)
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
