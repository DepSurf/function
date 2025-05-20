# Function: <code>sk_psock_verdict_recv</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_psock_verdict_recv(read_descriptor_t *desc, struct sk_buff *skb, unsigned int offset, size_t orig_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3f5b0)
Location: net/core/skmsg.c:937
Inline: False
```
**Symbols:**

```
ffffffff81a3f5b0-ffffffff81a3f74a: sk_psock_verdict_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_psock_verdict_recv(read_descriptor_t *desc, struct sk_buff *skb, unsigned int offset, size_t orig_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4e590)
Location: net/core/skmsg.c:1139
Inline: False
```
**Symbols:**

```
ffffffff81a4e590-ffffffff81a4e72d: sk_psock_verdict_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_psock_verdict_recv(read_descriptor_t *desc, struct sk_buff *skb, unsigned int offset, size_t orig_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b072d0)
Location: net/core/skmsg.c:1149
Inline: False
```
**Symbols:**

```
ffffffff81b072d0-ffffffff81b07469: sk_psock_verdict_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_psock_verdict_recv(read_descriptor_t *desc, struct sk_buff *skb, unsigned int offset, size_t orig_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8bd30)
Location: net/core/skmsg.c:1169
Inline: False
```
**Symbols:**

```
ffffffff81c8bd30-ffffffff81c8bed8: sk_psock_verdict_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_psock_verdict_recv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e48270)
Location: net/core/skmsg.c:1176
Inline: False
```
**Symbols:**

```
ffffffff81e48270-ffffffff81e4841f: sk_psock_verdict_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_psock_verdict_recv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3a50)
Location: net/core/skmsg.c:1172
Inline: False
```
**Symbols:**

```
ffffffff81ea3a50-ffffffff81ea3bc7: sk_psock_verdict_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_psock_verdict_recv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f66350)
Location: net/core/skmsg.c:1178
Inline: False
```
**Symbols:**

```
ffffffff81f66350-ffffffff81f664c7: sk_psock_verdict_recv (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>read_descriptor_t *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t orig_len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
