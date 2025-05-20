# Function: <code>mptcp_ioctl_outq</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_ioctl_outq(const struct mptcp_sock *msk, u64 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1c790)
Location: net/mptcp/protocol.c:3383
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_ioctl
```
**Symbols:**

```
ffffffff81e1c750-ffffffff81e1c80e: mptcp_ioctl_outq (STB_LOCAL)
ffffffff81f0fd4b-ffffffff81f0fd87: mptcp_ioctl_outq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_ioctl_outq(const struct mptcp_sock *msk, u64 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff4cc5)
Location: net/mptcp/protocol.c:3456
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_ioctl
```
**Symbols:**

```
ffffffff81ff4c70-ffffffff81ff4d41: mptcp_ioctl_outq (STB_LOCAL)
ffffffff820b6189-ffffffff820b61c5: mptcp_ioctl_outq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_ioctl_outq(const struct mptcp_sock *msk, u64 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff820711a0)
Location: net/mptcp/protocol.c:3519
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_ioctl
```
**Symbols:**

```
ffffffff82071150-ffffffff8207121b: mptcp_ioctl_outq (STB_LOCAL)
ffffffff821376aa-ffffffff821376de: mptcp_ioctl_outq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mptcp_ioctl_outq(const struct mptcp_sock *msk, u64 v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82145420)
Location: net/mptcp/protocol.c:3614
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_ioctl
```
**Symbols:**

```
ffffffff821453d0-ffffffff8214549b: mptcp_ioctl_outq (STB_LOCAL)
ffffffff82219535-ffffffff82219569: mptcp_ioctl_outq.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
