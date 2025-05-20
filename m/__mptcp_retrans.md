# Function: <code>__mptcp_retrans</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mptcp_retrans(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad4a0)
Location: net/mptcp/protocol.c:2305
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81bad4a0-ffffffff81bad803: __mptcp_retrans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mptcp_retrans(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2369
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81c7a8a0-ffffffff81c7acaf: __mptcp_retrans (STB_LOCAL)
ffffffff81d43631-ffffffff81d4369b: __mptcp_retrans.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mptcp_retrans(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2459
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81e1f8f0-ffffffff81e1fd52: __mptcp_retrans (STB_LOCAL)
ffffffff81f10113-ffffffff81f10167: __mptcp_retrans.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mptcp_retrans(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2491
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81ff6330-ffffffff81ff67b8: __mptcp_retrans (STB_LOCAL)
ffffffff820b6397-ffffffff820b6412: __mptcp_retrans.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mptcp_retrans(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2502
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff82072510-ffffffff8207292a: __mptcp_retrans (STB_LOCAL)
ffffffff8213788f-ffffffff821378d4: __mptcp_retrans.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mptcp_retrans(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2578
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff821466b0-ffffffff82146a6c: __mptcp_retrans (STB_LOCAL)
ffffffff82219654-ffffffff82219694: __mptcp_retrans.cold (STB_LOCAL)
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
