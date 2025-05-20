# Function: <code>mptcp_diag_fill_info</code>

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
void mptcp_diag_fill_info(struct mptcp_sock *msk, struct mptcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:868
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81f10bcd-ffffffff81f10bf7: mptcp_diag_fill_info.cold (STB_LOCAL)
ffffffff81e333c0-ffffffff81e334ed: mptcp_diag_fill_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_diag_fill_info(struct mptcp_sock *msk, struct mptcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:885
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff820b6ee9-ffffffff820b6f13: mptcp_diag_fill_info.cold (STB_LOCAL)
ffffffff8200c220-ffffffff8200c34d: mptcp_diag_fill_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_diag_fill_info(struct mptcp_sock *msk, struct mptcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:891
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
```
**Symbols:**

```
ffffffff8213821e-ffffffff82138248: mptcp_diag_fill_info.cold (STB_LOCAL)
ffffffff82088710-ffffffff820888f9: mptcp_diag_fill_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_diag_fill_info(struct mptcp_sock *msk, struct mptcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:905
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
```
**Symbols:**

```
ffffffff8221a03e-ffffffff8221a088: mptcp_diag_fill_info.cold (STB_LOCAL)
ffffffff8215e300-ffffffff8215e529: mptcp_diag_fill_info (STB_GLOBAL)
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
