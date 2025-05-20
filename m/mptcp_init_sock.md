# Function: <code>mptcp_init_sock</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab3e0)
Location: net/mptcp/protocol.c:1274
Inline: True
```
**Symbols:**

```
ffffffff81bab3e0-ffffffff81bab51d: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbda80)
Location: net/mptcp/protocol.c:2384
Inline: True
```
**Symbols:**

```
ffffffff81bbda80-ffffffff81bbdc5c: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad2f0)
Location: net/mptcp/protocol.c:2441
Inline: True
```
**Symbols:**

```
ffffffff81bad070-ffffffff81bad2e2: mptcp_init_sock.part.0 (STB_LOCAL)
ffffffff81c26273-ffffffff81c2628b: mptcp_init_sock.part.0.cold (STB_LOCAL)
ffffffff81bad2f0-ffffffff81bad351: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7a190)
Location: net/mptcp/protocol.c:2504
Inline: True
```
**Symbols:**

```
ffffffff81c79f10-ffffffff81c7a182: mptcp_init_sock.part.0 (STB_LOCAL)
ffffffff81d43520-ffffffff81d43538: mptcp_init_sock.part.0.cold (STB_LOCAL)
ffffffff81c7a190-ffffffff81c7a1f1: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1e930)
Location: net/mptcp/protocol.c:2654
Inline: True
```
**Symbols:**

```
ffffffff81e1e930-ffffffff81e1eb1a: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff57d0)
Location: net/mptcp/protocol.c:2700
Inline: True
```
**Symbols:**

```
ffffffff81ff57d0-ffffffff81ff59cd: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8206f4d0)
Location: net/mptcp/protocol.c:2709
Inline: False
```
**Symbols:**

```
ffffffff8206f4d0-ffffffff8206f5a0: mptcp_init_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_init_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff821435d0)
Location: net/mptcp/protocol.c:2793
Inline: False
```
**Symbols:**

```
ffffffff821435d0-ffffffff821436ac: mptcp_init_sock (STB_LOCAL)
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
