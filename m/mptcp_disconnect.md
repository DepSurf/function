# Function: <code>mptcp_disconnect</code>

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
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba9da0)
Location: net/mptcp/protocol.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81ba9da0-ffffffff81ba9daf: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbc870)
Location: net/mptcp/protocol.c:2646
Inline: False
```
**Symbols:**

```
ffffffff81bbc870-ffffffff81bbc943: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba9c80)
Location: net/mptcp/protocol.c:2721
Inline: False
```
**Symbols:**

```
ffffffff81ba9c80-ffffffff81ba9ce2: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c76ff0)
Location: net/mptcp/protocol.c:2778
Inline: False
```
**Symbols:**

```
ffffffff81c76ff0-ffffffff81c77052: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e23b40)
Location: net/mptcp/protocol.c:2913
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
```
**Symbols:**

```
ffffffff81e23b40-ffffffff81e23c46: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ffb9c8)
Location: net/mptcp/protocol.c:3001
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81ffb310-ffffffff81ffb416: mptcp_disconnect.part.0 (STB_LOCAL)
ffffffff81ffb430-ffffffff81ffb45a: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82077680)
Location: net/mptcp/protocol.c:3028
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff82077680-ffffffff820777fc: mptcp_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8214c6a0)
Location: net/mptcp/protocol.c:3126
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff8214c6a0-ffffffff8214c854: mptcp_disconnect (STB_LOCAL)
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
