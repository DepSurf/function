# Function: <code>unix_recvq_full_lockless</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b28dd0)
Location: net/unix/af_unix.c:197
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b37041)
Location: net/unix/af_unix.c:197
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b24c22)
Location: net/unix/af_unix.c:197
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be6c4e)
Location: net/unix/af_unix.c:198
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/unix/af_unix.c (ffffffff81d7d634)
Location: net/unix/af_unix.c:225
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4ae44)
Location: net/unix/af_unix.c:231
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faaaf0)
Location: net/unix/af_unix.c:232
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82077ee0)
Location: net/unix/af_unix.c:231
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
