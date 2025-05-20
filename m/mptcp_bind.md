# Function: <code>mptcp_bind</code>

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
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baa150)
Location: net/mptcp/protocol.c:1780
Inline: False
```
**Symbols:**

```
ffffffff81baa150-ffffffff81baa1db: mptcp_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb9e90)
Location: net/mptcp/protocol.c:3148
Inline: False
```
**Symbols:**

```
ffffffff81bb9e90-ffffffff81bb9f1e: mptcp_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba9270)
Location: net/mptcp/protocol.c:3135
Inline: False
```
**Symbols:**

```
ffffffff81ba9270-ffffffff81ba92fe: mptcp_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3228
Inline: False
```
**Symbols:**

```
ffffffff81c785b0-ffffffff81c78651: mptcp_bind (STB_LOCAL)
ffffffff81d43389-ffffffff81d433bc: mptcp_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3475
Inline: False
```
**Symbols:**

```
ffffffff81e1d810-ffffffff81e1d8bb: mptcp_bind (STB_LOCAL)
ffffffff81f0fe63-ffffffff81f0fe96: mptcp_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3614
Inline: False
```
**Symbols:**

```
ffffffff81ffac00-ffffffff81ffacab: mptcp_bind (STB_LOCAL)
ffffffff820b6700-ffffffff820b6733: mptcp_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82072c80)
Location: net/mptcp/protocol.c:3674
Inline: False
```
**Symbols:**

```
ffffffff82072c80-ffffffff82072d0c: mptcp_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_bind(struct socket *sock, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82146dd0)
Location: net/mptcp/protocol.c:3784
Inline: False
```
**Symbols:**

```
ffffffff82146dd0-ffffffff82146e7a: mptcp_bind (STB_LOCAL)
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
