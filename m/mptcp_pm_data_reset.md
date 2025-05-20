# Function: <code>mptcp_pm_data_reset</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_data_reset(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2d750)
Location: net/mptcp/pm.c:423
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/pm.c:mptcp_pm_data_init
```
**Symbols:**

```
ffffffff81e2d750-ffffffff81e2d86b: mptcp_pm_data_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_data_reset(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82005cb0)
Location: net/mptcp/pm.c:448
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_init
```
**Symbols:**

```
ffffffff82005cb0-ffffffff82005dcb: mptcp_pm_data_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_data_reset(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82082030)
Location: net/mptcp/pm.c:504
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/pm.c:mptcp_pm_data_init
```
**Symbols:**

```
ffffffff82082030-ffffffff82082146: mptcp_pm_data_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_data_reset(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82157620)
Location: net/mptcp/pm.c:497
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/pm.c:mptcp_pm_data_init
```
**Symbols:**

```
ffffffff82157620-ffffffff82157736: mptcp_pm_data_reset (STB_GLOBAL)
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
