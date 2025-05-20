# Function: <code>mptcp_pm_subflow_check_next</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_check_next(struct mptcp_sock *msk, const struct sock *ssk, const struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:178
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81f10a45-ffffffff81f10a91: mptcp_pm_subflow_check_next.cold (STB_LOCAL)
ffffffff81e2ce20-ffffffff81e2cf16: mptcp_pm_subflow_check_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_check_next(struct mptcp_sock *msk, const struct sock *ssk, const struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:178
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff820b6d70-ffffffff820b6dbc: mptcp_pm_subflow_check_next.cold (STB_LOCAL)
ffffffff820051f0-ffffffff820052e6: mptcp_pm_subflow_check_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_check_next(struct mptcp_sock *msk, const struct sock *ssk, const struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:187
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff82138106-ffffffff8213811b: mptcp_pm_subflow_check_next.cold (STB_LOCAL)
ffffffff820813e0-ffffffff820814e0: mptcp_pm_subflow_check_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_check_next(struct mptcp_sock *msk, const struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:187
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff82219f1c-ffffffff82219f31: mptcp_pm_subflow_check_next.cold (STB_LOCAL)
ffffffff82156a00-ffffffff82156afe: mptcp_pm_subflow_check_next (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct sock *ssk</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, ssk, subflow</code> ➡️ <code>msk, subflow</code>
</li>
</ul>
</details>
</li>
</ul>
