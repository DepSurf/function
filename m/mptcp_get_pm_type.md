# Function: <code>mptcp_get_pm_type</code>

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
int mptcp_get_pm_type(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81e2c7f0)
Location: net/mptcp/ctrl.c:67
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
**Symbols:**

```
ffffffff81e2c7f0-ffffffff81e2c82a: mptcp_get_pm_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_get_pm_type(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82004ae0)
Location: net/mptcp/ctrl.c:67
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
**Symbols:**

```
ffffffff82004ae0-ffffffff82004b1a: mptcp_get_pm_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_get_pm_type(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82080c80)
Location: net/mptcp/ctrl.c:67
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
**Symbols:**

```
ffffffff82080c80-ffffffff82080cba: mptcp_get_pm_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_get_pm_type(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82156250)
Location: net/mptcp/ctrl.c:76
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
```
**Symbols:**

```
ffffffff82156250-ffffffff8215628a: mptcp_get_pm_type (STB_GLOBAL)
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
