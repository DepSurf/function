# Function: <code>__mptcp_init_sock</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad6e5)
Location: net/mptcp/protocol.c:1251
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbaba0)
Location: net/mptcp/protocol.c:2353
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
**Symbols:**

```
ffffffff81bbaba0-ffffffff81bbad02: __mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba9b20)
Location: net/mptcp/protocol.c:2410
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
**Symbols:**

```
ffffffff81ba9b20-ffffffff81ba9c77: __mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c76e90)
Location: net/mptcp/protocol.c:2472
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
**Symbols:**

```
ffffffff81c76e90-ffffffff81c76fea: __mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1ba90)
Location: net/mptcp/protocol.c:2612
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
**Symbols:**

```
ffffffff81e1ba90-ffffffff81e1bbec: __mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff2f80)
Location: net/mptcp/protocol.c:2658
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
**Symbols:**

```
ffffffff81ff2f80-ffffffff81ff30dc: __mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8206f200)
Location: net/mptcp/protocol.c:2666
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_init_sock
```
**Symbols:**

```
ffffffff8206f200-ffffffff8206f366: __mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82143300)
Location: net/mptcp/protocol.c:2751
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_init_sock
```
**Symbols:**

```
ffffffff82143300-ffffffff8214346d: __mptcp_init_sock (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
