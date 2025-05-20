# Function: <code>mptcp_stream_accept</code>

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
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81babe20)
Location: net/mptcp/protocol.c:1921
Inline: False
```
**Symbols:**

```
ffffffff81babe20-ffffffff81bac09c: mptcp_stream_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbe220)
Location: net/mptcp/protocol.c:3259
Inline: False
```
**Symbols:**

```
ffffffff81bbe220-ffffffff81bbe67a: mptcp_stream_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad9b0)
Location: net/mptcp/protocol.c:3250
Inline: False
```
**Symbols:**

```
ffffffff81bad9b0-ffffffff81badd7e: mptcp_stream_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3343
Inline: False
```
**Symbols:**

```
ffffffff81c7a3e0-ffffffff81c7a7c3: mptcp_stream_accept (STB_LOCAL)
ffffffff81d435ac-ffffffff81d43602: mptcp_stream_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3599
Inline: False
```
**Symbols:**

```
ffffffff81e1eb20-ffffffff81e1ee12: mptcp_stream_accept (STB_LOCAL)
ffffffff81f10003-ffffffff81f1004a: mptcp_stream_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3679
Inline: False
```
**Symbols:**

```
ffffffff81ff54b0-ffffffff81ff57bc: mptcp_stream_accept (STB_LOCAL)
ffffffff820b62ae-ffffffff820b62fd: mptcp_stream_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82076250)
Location: net/mptcp/protocol.c:3734
Inline: False
```
**Symbols:**

```
ffffffff82076250-ffffffff82076458: mptcp_stream_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mptcp_stream_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3851
Inline: False
```
**Symbols:**

```
ffffffff8214aa80-ffffffff8214adf5: mptcp_stream_accept (STB_LOCAL)
ffffffff8221991b-ffffffff82219951: mptcp_stream_accept.cold (STB_LOCAL)
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
