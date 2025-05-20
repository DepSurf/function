# Function: <code>__mptcp_space</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc32da)
Location: net/mptcp/protocol.h:300
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81bc4ac5)
Location: net/mptcp/protocol.h:300
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81badfe7)
Location: net/mptcp/protocol.h:301
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81bb360a)
Location: net/mptcp/protocol.h:301
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81bb514f)
Location: net/mptcp/protocol.h:301
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7b266)
Location: net/mptcp/protocol.h:313
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81c81d28)
Location: net/mptcp/protocol.h:313
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81c83998)
Location: net/mptcp/protocol.h:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e202af)
Location: net/mptcp/protocol.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81e278b8)
Location: net/mptcp/protocol.h:336
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81e299a6)
Location: net/mptcp/protocol.h:336
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff7788)
Location: net/mptcp/protocol.h:349
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81fff788)
Location: net/mptcp/protocol.h:349
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff82001a96)
Location: net/mptcp/protocol.h:349
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82073c76)
Location: net/mptcp/protocol.h:353
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff8207b858)
Location: net/mptcp/protocol.h:353
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff8207df56)
Location: net/mptcp/protocol.h:353
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_dss
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff821481c2)
Location: net/mptcp/protocol.h:364
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff8215138a)
Location: net/mptcp/protocol.h:364
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff82153469)
Location: net/mptcp/protocol.h:364
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_dss
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
