# Function: <code>mptcp_event_add_subflow</code>

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
int mptcp_event_add_subflow(struct sk_buff *skb, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb8100)
Location: net/mptcp/pm_netlink.c:1587
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
```
**Symbols:**

```
ffffffff81bb8100-ffffffff81bb82d4: mptcp_event_add_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_event_add_subflow(struct sk_buff *skb, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1777
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
```
**Symbols:**

```
ffffffff81c87780-ffffffff81c87963: mptcp_event_add_subflow (STB_LOCAL)
ffffffff81d43fed-ffffffff81d4400d: mptcp_event_add_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_event_add_subflow(struct sk_buff *skb, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1931
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
```
**Symbols:**

```
ffffffff81e2df90-ffffffff81e2e172: mptcp_event_add_subflow (STB_LOCAL)
ffffffff81f10b03-ffffffff81f10b23: mptcp_event_add_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_event_add_subflow(struct sk_buff *skb, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1945
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
```
**Symbols:**

```
ffffffff82007000-ffffffff820071e2: mptcp_event_add_subflow (STB_LOCAL)
ffffffff820b6e2e-ffffffff820b6e4e: mptcp_event_add_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mptcp_event_add_subflow(struct sk_buff *skb, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1961
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
```
**Symbols:**

```
ffffffff820833a0-ffffffff8208358e: mptcp_event_add_subflow (STB_LOCAL)
ffffffff8213818d-ffffffff821381a6: mptcp_event_add_subflow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mptcp_event_add_subflow(struct sk_buff *skb, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1960
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
```
**Symbols:**

```
ffffffff82158b20-ffffffff82158d1a: mptcp_event_add_subflow (STB_LOCAL)
ffffffff82219fa3-ffffffff82219fbc: mptcp_event_add_subflow.cold (STB_LOCAL)
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
