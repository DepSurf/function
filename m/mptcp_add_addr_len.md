# Function: <code>mptcp_add_addr_len</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb0d98)
Location: net/mptcp/protocol.h:425
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_addr
```
```
In net/mptcp/pm.c (ffffffff81bb2847)
Location: net/mptcp/protocol.h:425
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_addr_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc43b9)
Location: net/mptcp/protocol.h:593
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81bc6cb0)
Location: net/mptcp/protocol.h:593
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/options.c (ffffffff81bb4b31)
Location: net/mptcp/protocol.h:733
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81bb79bb)
Location: net/mptcp/protocol.h:733
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/options.c (ffffffff81c83491)
Location: net/mptcp/protocol.h:788
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81c86e15)
Location: net/mptcp/protocol.h:788
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/options.c (ffffffff81e293f3)
Location: net/mptcp/protocol.h:854
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81e2d4ea)
Location: net/mptcp/protocol.h:854
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/options.c (ffffffff82001443)
Location: net/mptcp/protocol.h:886
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff8200593a)
Location: net/mptcp/protocol.h:886
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/options.c (ffffffff8207d5d9)
Location: net/mptcp/protocol.h:899
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff82081b2a)
Location: net/mptcp/protocol.h:899
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/options.c (ffffffff82152ac9)
Location: net/mptcp/protocol.h:993
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff8215711a)
Location: net/mptcp/protocol.h:993
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
