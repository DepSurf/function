# Function: <code>mptcp_pm_get_local_id</code>

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
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb28b0)
Location: net/mptcp/pm.c:179
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_rebuild_header
```
**Symbols:**

```
ffffffff81bb28b0-ffffffff81bb28c0: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6da0)
Location: net/mptcp/pm.c:262
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bc6da0-ffffffff81bc6db0: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7ad0)
Location: net/mptcp/pm.c:306
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81bb7ad0-ffffffff81bb7ae0: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86fb0)
Location: net/mptcp/pm.c:339
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81c86fb0-ffffffff81c86fc0: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2d6a0)
Location: net/mptcp/pm.c:399
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff81e2d6a0-ffffffff81e2d6b8: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82005b10)
Location: net/mptcp/pm.c:399
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff82005b10-ffffffff82005b28: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82081d00)
Location: net/mptcp/pm.c:416
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff82081d00-ffffffff82081dd4: mptcp_pm_get_local_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_get_local_id(struct mptcp_sock *msk, struct sock_common *skc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff821572f0)
Location: net/mptcp/pm.c:409
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_rebuild_header
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/subflow.c:subflow_check_req
```
**Symbols:**

```
ffffffff821572f0-ffffffff821573c4: mptcp_pm_get_local_id (STB_GLOBAL)
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
