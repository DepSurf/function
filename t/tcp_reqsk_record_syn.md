# Function: <code>tcp_reqsk_record_syn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176e102)
Location: net/ipv4/tcp_input.c:6139
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dc51b)
Location: net/ipv4/tcp_input.c:6192
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180c5ed)
Location: net/ipv4/tcp_input.c:6284
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8182c52a)
Location: net/ipv4/tcp_input.c:6282
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff818ab3fd)
Location: net/ipv4/tcp_input.c:6179
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8190083d)
Location: net/ipv4/tcp_input.c:6343
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192ed03)
Location: net/ipv4/tcp_input.c:6394
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198deb0)
Location: net/ipv4/tcp_input.c:6452
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff8198deb0-ffffffff8198df45: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c4a80)
Location: net/ipv4/tcp_input.c:6506
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819c4a80-ffffffff819c4b15: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaff40)
Location: net/ipv4/tcp_input.c:6565
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81aaff40-ffffffff81aaffdc: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abaf80)
Location: net/ipv4/tcp_input.c:6701
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81abaf80-ffffffff81abb06e: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa5f40)
Location: net/ipv4/tcp_input.c:6710
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81aa5f40-ffffffff81aa602e: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62320)
Location: net/ipv4/tcp_input.c:6745
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81b62320-ffffffff81b6240e: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf15b0)
Location: net/ipv4/tcp_input.c:6831
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81cf15b0-ffffffff81cf16c4: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5db0)
Location: net/ipv4/tcp_input.c:6861
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81eb5db0-ffffffff81eb5ec4: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f141d0)
Location: net/ipv4/tcp_input.c:6868
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81f141d0-ffffffff81f142e4: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd86b0)
Location: net/ipv4/tcp_input.c:7028
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81fd86b0-ffffffff81fd87c4: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7aa14)
Location: net/ipv4/tcp_input.c:6506
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d88224)
Location: net/ipv4/tcp_input.c:6506
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7f8f0)
Location: net/ipv4/tcp_input.c:6506
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
c000000000d7f8f0-c000000000d7f9b8: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007de5a4)
Location: net/ipv4/tcp_input.c:6506
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819648f0)
Location: net/ipv4/tcp_input.c:6506
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819648f0-ffffffff81964985: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191e3e0)
Location: net/ipv4/tcp_input.c:6506
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff8191e3e0-ffffffff8191e475: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cf0c0)
Location: net/ipv4/tcp_input.c:6506
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819cf0c0-ffffffff819cf155: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_reqsk_record_syn(const struct sock *sk, struct request_sock *req, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d8c50)
Location: net/ipv4/tcp_input.c:6506
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819d8c50-ffffffff819d8ce5: tcp_reqsk_record_syn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
