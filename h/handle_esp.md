# Function: <code>handle_esp</code>

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
void handle_esp(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b22780)
Location: net/xfrm/espintcp.c:30
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81b22780-ffffffff81b22845: handle_esp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_esp(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b31440)
Location: net/xfrm/espintcp.c:30
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81b31440-ffffffff81b314f8: handle_esp (STB_LOCAL)
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
In net/xfrm/espintcp.c (ffffffff81b1f252)
Location: net/xfrm/espintcp.c:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
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
In net/xfrm/espintcp.c (ffffffff81be3e3e)
Location: net/xfrm/espintcp.c:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
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
In net/xfrm/espintcp.c (ffffffff81d7adfa)
Location: net/xfrm/espintcp.c:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_esp(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81f47f50)
Location: net/xfrm/espintcp.c:30
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81f47f50-ffffffff81f4801d: handle_esp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_esp(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81fa7a50)
Location: net/xfrm/espintcp.c:31
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81fa7a50-ffffffff81fa7b1d: handle_esp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_esp(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff82074d10)
Location: net/xfrm/espintcp.c:31
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff82074d10-ffffffff82074ddd: handle_esp (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
