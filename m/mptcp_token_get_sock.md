# Function: <code>mptcp_token_get_sock</code>

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
struct mptcp_sock *mptcp_token_get_sock(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb1c70)
Location: net/mptcp/token.c:153
Inline: False
```
**Symbols:**

```
ffffffff81bb1c70-ffffffff81bb1cfc: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bc5be0)
Location: net/mptcp/token.c:242
Inline: False
Direct callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff81bc5be0-ffffffff81bc5cd5: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81bb6750)
Location: net/mptcp/token.c:242
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff81bb6750-ffffffff81bb683e: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(struct net *net, u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81c85760)
Location: net/mptcp/token.c:242
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff81c85760-ffffffff81c85869: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(struct net *net, u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff81e2b9a0)
Location: net/mptcp/token.c:242
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff81e2b9a0-ffffffff81e2bac8: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(struct net *net, u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff82003b80)
Location: net/mptcp/token.c:242
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff82003b80-ffffffff82003ca8: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(struct net *net, u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff8207fce0)
Location: net/mptcp/token.c:246
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff8207fce0-ffffffff8207fdfd: mptcp_token_get_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mptcp_sock *mptcp_token_get_sock(struct net *net, u32 token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/token.c (ffffffff821551d0)
Location: net/mptcp/token.c:246
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff821551d0-ffffffff821552ed: mptcp_token_get_sock (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>token</code> ➡️ <code>net, token</code>
</li>
</ul>
</details>
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
