# Function: <code>mptcp_can_accept_new_subflow</code>

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
In net/mptcp/subflow.c (ffffffff81bc1cb1)
Location: net/mptcp/subflow.c:57
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
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
In net/mptcp/subflow.c (ffffffff81bb25b4)
Location: net/mptcp/subflow.c:62
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:62
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81c7f880-ffffffff81c7f8e1: mptcp_can_accept_new_subflow (STB_LOCAL)
ffffffff81d4395e-ffffffff81d4398e: mptcp_can_accept_new_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:62
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81e25220-ffffffff81e252aa: mptcp_can_accept_new_subflow (STB_LOCAL)
ffffffff81f10465-ffffffff81f10495: mptcp_can_accept_new_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:61
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81ffce40-ffffffff81ffceca: mptcp_can_accept_new_subflow (STB_LOCAL)
ffffffff820b681f-ffffffff820b684f: mptcp_can_accept_new_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:62
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff82079110-ffffffff8207919a: mptcp_can_accept_new_subflow (STB_LOCAL)
ffffffff82137b9d-ffffffff82137bcd: mptcp_can_accept_new_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:62
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff8214e560-ffffffff8214e5ea: mptcp_can_accept_new_subflow (STB_LOCAL)
ffffffff82219a6b-ffffffff82219a9b: mptcp_can_accept_new_subflow.cold (STB_LOCAL)
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
