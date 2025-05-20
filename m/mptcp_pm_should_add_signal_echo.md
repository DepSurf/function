# Function: <code>mptcp_pm_should_add_signal_echo</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6c8b)
Location: net/mptcp/protocol.h:573
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
In net/mptcp/options.c (ffffffff81bb4ad6)
Location: net/mptcp/protocol.h:713
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81bb7997)
Location: net/mptcp/protocol.h:713
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/pm.c (ffffffff81c86da7)
Location: net/mptcp/protocol.h:778
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/pm.c (ffffffff81e2d4be)
Location: net/mptcp/protocol.h:834
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/pm.c (ffffffff8200590e)
Location: net/mptcp/protocol.h:866
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/pm.c (ffffffff82081afe)
Location: net/mptcp/protocol.h:879
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/mptcp/pm.c (ffffffff821570ee)
Location: net/mptcp/protocol.h:973
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
