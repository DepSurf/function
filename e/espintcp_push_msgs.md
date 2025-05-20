# Function: <code>espintcp_push_msgs</code>

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
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b22cc0)
Location: net/xfrm/espintcp.c:248
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81b22cc0-ffffffff81b22ddd: espintcp_push_msgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b316b0)
Location: net/xfrm/espintcp.c:252
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81b316b0-ffffffff81b317cd: espintcp_push_msgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b1f3e0)
Location: net/xfrm/espintcp.c:252
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81b1f3e0-ffffffff81b1f4fd: espintcp_push_msgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:252
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81be4030-ffffffff81be4163: espintcp_push_msgs (STB_LOCAL)
ffffffff81d3efc3-ffffffff81d3efd7: espintcp_push_msgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:250
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81d7b490-ffffffff81d7b5f1: espintcp_push_msgs (STB_LOCAL)
ffffffff81f0b91e-ffffffff81f0b933: espintcp_push_msgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:250
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81f48510-ffffffff81f48671: espintcp_push_msgs (STB_LOCAL)
ffffffff820b3177-ffffffff820b318c: espintcp_push_msgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:257
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff81fa8380-ffffffff81fa84e1: espintcp_push_msgs (STB_LOCAL)
ffffffff82134375-ffffffff8213438a: espintcp_push_msgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int espintcp_push_msgs(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:257
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_push_skb
  - net/xfrm/espintcp.c:espintcp_push_skb
```
**Symbols:**

```
ffffffff82075670-ffffffff820757d1: espintcp_push_msgs (STB_LOCAL)
ffffffff82215f3e-ffffffff82215f53: espintcp_push_msgs.cold (STB_LOCAL)
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
