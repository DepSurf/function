# Function: <code>mptcp_pm_subflow_chk_stale</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_pm_subflow_chk_stale(const struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86fc0)
Location: net/mptcp/pm.c:344
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
**Symbols:**

```
ffffffff81c86fc0-ffffffff81c8701f: mptcp_pm_subflow_chk_stale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_subflow_chk_stale(const struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2d6c0)
Location: net/mptcp/pm.c:404
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
**Symbols:**

```
ffffffff81e2d6c0-ffffffff81e2d74a: mptcp_pm_subflow_chk_stale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_subflow_chk_stale(const struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82005b40)
Location: net/mptcp/pm.c:404
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
**Symbols:**

```
ffffffff82005b40-ffffffff82005bca: mptcp_pm_subflow_chk_stale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_subflow_chk_stale(const struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82081ec0)
Location: net/mptcp/pm.c:460
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
**Symbols:**

```
ffffffff82081ec0-ffffffff82081f4a: mptcp_pm_subflow_chk_stale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_subflow_chk_stale(const struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff821574b0)
Location: net/mptcp/pm.c:453
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_retrans
```
**Symbols:**

```
ffffffff821574b0-ffffffff8215753a: mptcp_pm_subflow_chk_stale (STB_GLOBAL)
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
