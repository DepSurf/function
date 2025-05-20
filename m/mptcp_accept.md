# Function: <code>mptcp_accept</code>

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
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bac700)
Location: net/mptcp/protocol.c:1488
Inline: False
```
**Symbols:**

```
ffffffff81bac700-ffffffff81bac907: mptcp_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbd670)
Location: net/mptcp/protocol.c:2740
Inline: False
```
**Symbols:**

```
ffffffff81bbd670-ffffffff81bbd80b: mptcp_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad810)
Location: net/mptcp/protocol.c:2817
Inline: False
```
**Symbols:**

```
ffffffff81bad810-ffffffff81bad9a7: mptcp_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2876
Inline: False
```
**Symbols:**

```
ffffffff81c7a200-ffffffff81c7a3d4: mptcp_accept (STB_LOCAL)
ffffffff81d43538-ffffffff81d435ac: mptcp_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3030
Inline: False
```
**Symbols:**

```
ffffffff81e1e760-ffffffff81e1e92a: mptcp_accept (STB_LOCAL)
ffffffff81f0ff8f-ffffffff81f10003: mptcp_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3116
Inline: False
```
**Symbols:**

```
ffffffff81ff52d0-ffffffff81ff5497: mptcp_accept (STB_LOCAL)
ffffffff820b623a-ffffffff820b62ae: mptcp_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3178
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
```
**Symbols:**

```
ffffffff8206ffa0-ffffffff820700f9: mptcp_accept (STB_LOCAL)
ffffffff82137586-ffffffff821375b6: mptcp_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
