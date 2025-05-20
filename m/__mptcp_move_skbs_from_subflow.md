# Function: <code>__mptcp_move_skbs_from_subflow</code>

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
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab750)
Location: net/mptcp/protocol.c:194
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:move_skbs_to_msk
```
**Symbols:**

```
ffffffff81bab750-ffffffff81bab9e6: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbd3e0)
Location: net/mptcp/protocol.c:530
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81bbd3e0-ffffffff81bbd66b: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bacbf0)
Location: net/mptcp/protocol.c:532
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81bacbf0-ffffffff81bace8d: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c795a0)
Location: net/mptcp/protocol.c:558
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81c795a0-ffffffff81c7983d: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1e4f0)
Location: net/mptcp/protocol.c:627
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81e1e4f0-ffffffff81e1e755: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff6f20)
Location: net/mptcp/protocol.c:619
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81ff6f20-ffffffff81ff7185: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82073600)
Location: net/mptcp/protocol.c:631
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff82073600-ffffffff82073858: __mptcp_move_skbs_from_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __mptcp_move_skbs_from_subflow(struct mptcp_sock *msk, struct sock *ssk, unsigned int *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82147860)
Location: net/mptcp/protocol.c:619
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff82147860-ffffffff82147ab8: __mptcp_move_skbs_from_subflow (STB_LOCAL)
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
