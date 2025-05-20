# Function: <code>subflow_check_data_avail</code>

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
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81baf500)
Location: net/mptcp/subflow.c:745
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff81baf500-ffffffff81baf7f7: subflow_check_data_avail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc2210)
Location: net/mptcp/subflow.c:894
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff81bc2210-ffffffff81bc24d8: subflow_check_data_avail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb2c30)
Location: net/mptcp/subflow.c:992
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff81bb2c30-ffffffff81bb3008: subflow_check_data_avail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1105
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff81c811c0-ffffffff81c816b7: subflow_check_data_avail (STB_LOCAL)
ffffffff81d43abf-ffffffff81d43adc: subflow_check_data_avail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1189
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff81e26be0-ffffffff81e27146: subflow_check_data_avail (STB_LOCAL)
ffffffff81f105c5-ffffffff81f10621: subflow_check_data_avail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1261
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff81ffe370-ffffffff81ffe8a8: subflow_check_data_avail (STB_LOCAL)
ffffffff820b6881-ffffffff820b68dd: subflow_check_data_avail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1232
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff8207a440-ffffffff8207a9b2: subflow_check_data_avail (STB_LOCAL)
ffffffff82137bff-ffffffff82137c5b: subflow_check_data_avail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool subflow_check_data_avail(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1257
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:mptcp_subflow_data_available
```
**Symbols:**

```
ffffffff8214f8a0-ffffffff8214fe1c: subflow_check_data_avail (STB_LOCAL)
ffffffff82219acd-ffffffff82219b3d: subflow_check_data_avail.cold (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
