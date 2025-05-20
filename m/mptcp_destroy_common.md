# Function: <code>mptcp_destroy_common</code>

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
void mptcp_destroy_common(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bc0900)
Location: net/mptcp/protocol.c:2786
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81bc0900-ffffffff81bc09a1: mptcp_destroy_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb06c0)
Location: net/mptcp/protocol.c:2863
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81bb06c0-ffffffff81bb0761: mptcp_destroy_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7e580)
Location: net/mptcp/protocol.c:2924
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81c7e580-ffffffff81c7e777: mptcp_destroy_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock *msk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e239a0)
Location: net/mptcp/protocol.c:3078
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81e239a0-ffffffff81e23b3c: mptcp_destroy_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock *msk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ffb0e0)
Location: net/mptcp/protocol.c:3164
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_destroy
```
**Symbols:**

```
ffffffff81ffb0e0-ffffffff81ffb27c: mptcp_destroy_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock *msk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82077460)
Location: net/mptcp/protocol.c:3224
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_destroy
  - net/mptcp/protocol.c:mptcp_disconnect
```
**Symbols:**

```
ffffffff82077460-ffffffff820775ed: mptcp_destroy_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock *msk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8214c490)
Location: net/mptcp/protocol.c:3322
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_destroy
  - net/mptcp/protocol.c:mptcp_disconnect
```
**Symbols:**

```
ffffffff8214c490-ffffffff8214c623: mptcp_destroy_common (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
