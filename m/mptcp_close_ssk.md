# Function: <code>mptcp_close_ssk</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb038a)
Location: net/mptcp/protocol.c:2222
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
**Symbols:**

```
ffffffff81baed60-ffffffff81baedad: mptcp_close_ssk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7e22d)
Location: net/mptcp/protocol.c:2287
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
**Symbols:**

```
ffffffff81c7df80-ffffffff81c7dfcd: mptcp_close_ssk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e2360b)
Location: net/mptcp/protocol.c:2371
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
**Symbols:**

```
ffffffff81e22f50-ffffffff81e22fbc: mptcp_close_ssk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ffa35d)
Location: net/mptcp/protocol.c:2384
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
**Symbols:**

```
ffffffff81ff9cc0-ffffffff81ff9d2c: mptcp_close_ssk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82076a60)
Location: net/mptcp/protocol.c:2393
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
**Symbols:**

```
ffffffff820761d0-ffffffff8207623c: mptcp_close_ssk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8214b4f3)
Location: net/mptcp/protocol.c:2478
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
```
**Symbols:**

```
ffffffff8214aa00-ffffffff8214aa69: mptcp_close_ssk (STB_GLOBAL)
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
