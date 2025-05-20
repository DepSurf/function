# Function: <code>__mptcp_subflow_push_pending</code>

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
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbe940)
Location: net/mptcp/protocol.c:1522
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff81bbe940-ffffffff81bbec89: __mptcp_subflow_push_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bae910)
Location: net/mptcp/protocol.c:1557
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff81bae910-ffffffff81baed37: __mptcp_subflow_push_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1600
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff81c7c4c0-ffffffff81c7c7d1: __mptcp_subflow_push_pending (STB_LOCAL)
ffffffff81d437f2-ffffffff81d43806: __mptcp_subflow_push_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1634
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff81e21850-ffffffff81e21b2e: __mptcp_subflow_push_pending (STB_LOCAL)
ffffffff81f102d8-ffffffff81f102ed: __mptcp_subflow_push_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1596
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff81ff8d30-ffffffff81ff9008: __mptcp_subflow_push_pending (STB_LOCAL)
ffffffff820b65b2-ffffffff820b65c7: __mptcp_subflow_push_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1569
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff82075200-ffffffff820754f3: __mptcp_subflow_push_pending (STB_LOCAL)
ffffffff82137a45-ffffffff82137a5a: __mptcp_subflow_push_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mptcp_subflow_push_pending(struct sock *sk, struct sock *ssk, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1623
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
```
**Symbols:**

```
ffffffff821493a0-ffffffff8214976b: __mptcp_subflow_push_pending (STB_LOCAL)
ffffffff822197e9-ffffffff82219845: __mptcp_subflow_push_pending.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool first</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
