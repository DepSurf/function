# Function: <code>mptcp_setsockopt</code>

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
int mptcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baa430)
Location: net/mptcp/protocol.c:1560
Inline: False
```
**Symbols:**

```
ffffffff81baa430-ffffffff81baa4c9: mptcp_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bba950)
Location: net/mptcp/protocol.c:2866
Inline: False
```
**Symbols:**

```
ffffffff81bba950-ffffffff81bbab99: mptcp_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbc820)
Location: net/mptcp/sockopt.c:569
Inline: False
```
**Symbols:**

```
ffffffff81bbc820-ffffffff81bbc9eb: mptcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81c8c600)
Location: net/mptcp/sockopt.c:611
Inline: False
```
**Symbols:**

```
ffffffff81c8c600-ffffffff81c8c854: mptcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e34a40)
Location: net/mptcp/sockopt.c:804
Inline: False
```
**Symbols:**

```
ffffffff81e34a40-ffffffff81e34d49: mptcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200d6a0)
Location: net/mptcp/sockopt.c:821
Inline: False
```
**Symbols:**

```
ffffffff8200d6a0-ffffffff8200d9a9: mptcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8208a030)
Location: net/mptcp/sockopt.c:825
Inline: False
```
**Symbols:**

```
ffffffff8208a030-ffffffff8208a376: mptcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215fb10)
Location: net/mptcp/sockopt.c:840
Inline: False
```
**Symbols:**

```
ffffffff8215fb10-ffffffff8215fd94: mptcp_setsockopt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
