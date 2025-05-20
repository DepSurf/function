# Function: <code>mptcp_sendmsg</code>

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
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bace90)
Location: net/mptcp/protocol.c:742
Inline: False
```
**Symbols:**

```
ffffffff81bace90-ffffffff81bad48c: mptcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbf870)
Location: net/mptcp/protocol.c:1582
Inline: False
```
**Symbols:**

```
ffffffff81bbf870-ffffffff81bbfecf: mptcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baf3d0)
Location: net/mptcp/protocol.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81baf3d0-ffffffff81bafd79: mptcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1672
Inline: False
```
**Symbols:**

```
ffffffff81c7d0d0-ffffffff81c7d81a: mptcp_sendmsg (STB_LOCAL)
ffffffff81d43885-ffffffff81d4389f: mptcp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1705
Inline: False
```
**Symbols:**

```
ffffffff81e227a0-ffffffff81e22c8e: mptcp_sendmsg (STB_LOCAL)
ffffffff81f10385-ffffffff81f1039f: mptcp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1700
Inline: False
```
**Symbols:**

```
ffffffff81ffb470-ffffffff81ffbaee: mptcp_sendmsg (STB_LOCAL)
ffffffff820b6760-ffffffff820b67d5: mptcp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1697
Inline: False
```
**Symbols:**

```
ffffffff82077810-ffffffff82077ed0: mptcp_sendmsg (STB_LOCAL)
ffffffff82137b25-ffffffff82137b54: mptcp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1769
Inline: False
```
**Symbols:**

```
ffffffff8214c870-ffffffff8214cfe7: mptcp_sendmsg (STB_LOCAL)
ffffffff822199e3-ffffffff82219a22: mptcp_sendmsg.cold (STB_LOCAL)
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
