# Function: <code>queue_oob</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be8ff1)
Location: net/unix/af_unix.c:1965
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d81675)
Location: net/unix/af_unix.c:2052
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int queue_oob(struct socket *sock, struct msghdr *msg, struct sock *other);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4c700)
Location: net/unix/af_unix.c:2107
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81f4c700-ffffffff81f4c8e2: queue_oob (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int queue_oob(struct socket *sock, struct msghdr *msg, struct sock *other, struct scm_cookie *scm, bool fds_sent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fad7c0)
Location: net/unix/af_unix.c:2117
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81fad7c0-ffffffff81fad9cb: queue_oob (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int queue_oob(struct socket *sock, struct msghdr *msg, struct sock *other, struct scm_cookie *scm, bool fds_sent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8207a090)
Location: net/unix/af_unix.c:2123
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff8207a090-ffffffff8207a29b: queue_oob (STB_LOCAL)
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
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scm_cookie *scm</code>
</li>
<li>
<b>Param added. </b>
<code>bool fds_sent</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
