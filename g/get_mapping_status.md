# Function: <code>get_mapping_status</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:617
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81baf0f0-ffffffff81baf4f7: get_mapping_status (STB_LOCAL)
ffffffff81bb0329-ffffffff81bb0358: get_mapping_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:739
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81bc1d10-ffffffff81bc2208: get_mapping_status (STB_LOCAL)
ffffffff81c33f00-ffffffff81c33f2f: get_mapping_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb2670)
Location: net/mptcp/subflow.c:830
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81bb2670-ffffffff81bb2b5c: get_mapping_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:927
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81c80b30-ffffffff81c810f0: get_mapping_status (STB_LOCAL)
ffffffff81d43a8e-ffffffff81d43abf: get_mapping_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:970
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81e26580-ffffffff81e26af5: get_mapping_status (STB_LOCAL)
ffffffff81f10593-ffffffff81f105c5: get_mapping_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1042
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81ffdcb0-ffffffff81ffe264: get_mapping_status (STB_LOCAL)
ffffffff820b684f-ffffffff820b6881: get_mapping_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1018
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff82079e90-ffffffff8207a425: get_mapping_status (STB_LOCAL)
ffffffff82137bcd-ffffffff82137bff: get_mapping_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum mapping_status get_mapping_status(struct sock *ssk, struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1043
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff8214f2f0-ffffffff8214f885: get_mapping_status (STB_LOCAL)
ffffffff82219a9b-ffffffff82219acd: get_mapping_status.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mptcp_sock *msk</code>
</li>
</ul>
</details>
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
