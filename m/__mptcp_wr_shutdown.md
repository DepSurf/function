# Function: <code>__mptcp_wr_shutdown</code>

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
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbfed0)
Location: net/mptcp/protocol.c:2526
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81bbfed0-ffffffff81bbff4c: __mptcp_wr_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bafd80)
Location: net/mptcp/protocol.c:2596
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81bafd80-ffffffff81bafdfc: __mptcp_wr_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2653
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81c7cc10-ffffffff81c7cc9d: __mptcp_wr_shutdown (STB_LOCAL)
ffffffff81d43858-ffffffff81d43885: __mptcp_wr_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2797
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81e22010-ffffffff81e220b0: __mptcp_wr_shutdown (STB_LOCAL)
ffffffff81f1033f-ffffffff81f1036c: __mptcp_wr_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2845
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close
```
**Symbols:**

```
ffffffff81ff95b0-ffffffff81ff964f: __mptcp_wr_shutdown (STB_LOCAL)
ffffffff820b6619-ffffffff820b6646: __mptcp_wr_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2843
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close
```
**Symbols:**

```
ffffffff82075a80-ffffffff82075b22: __mptcp_wr_shutdown (STB_LOCAL)
ffffffff82137a9a-ffffffff82137ac5: __mptcp_wr_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mptcp_wr_shutdown(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2948
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close
```
**Symbols:**

```
ffffffff8214a0f0-ffffffff8214a192: __mptcp_wr_shutdown (STB_LOCAL)
ffffffff8221989e-ffffffff822198c9: __mptcp_wr_shutdown.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
