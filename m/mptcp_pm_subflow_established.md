# Function: <code>mptcp_pm_subflow_established</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb2690)
Location: net/mptcp/pm.c:109
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb2690-ffffffff81bb2715: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6990)
Location: net/mptcp/pm.c:148
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bc6990-ffffffff81bc6a15: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7560)
Location: net/mptcp/pm.c:156
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81bb7560-ffffffff81bb75e5: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:158
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81d43edc-ffffffff81d43f04: mptcp_pm_subflow_established.cold (STB_LOCAL)
ffffffff81c868b0-ffffffff81c8693e: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:161
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81f10a1b-ffffffff81f10a45: mptcp_pm_subflow_established.cold (STB_LOCAL)
ffffffff81e2cd70-ffffffff81e2ce17: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:161
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff820b6d46-ffffffff820b6d70: mptcp_pm_subflow_established.cold (STB_LOCAL)
ffffffff82005130-ffffffff820051d7: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:170
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff821380dc-ffffffff82138106: mptcp_pm_subflow_established.cold (STB_LOCAL)
ffffffff82081320-ffffffff820813c7: mptcp_pm_subflow_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_subflow_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:170
Inline: False
Direct callers:
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff82219ef2-ffffffff82219f1c: mptcp_pm_subflow_established.cold (STB_LOCAL)
ffffffff82156940-ffffffff821569e7: mptcp_pm_subflow_established (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mptcp_subflow_context *subflow</code>
</li>
</ul>
</details>
</li>
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
