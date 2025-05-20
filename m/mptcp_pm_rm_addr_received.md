# Function: <code>mptcp_pm_rm_addr_received</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, u8 rm_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6bd0)
Location: net/mptcp/pm.c:199
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bc6bd0-ffffffff81bc6c37: mptcp_pm_rm_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7820)
Location: net/mptcp/pm.c:223
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb7820-ffffffff81bb78c3: mptcp_pm_rm_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86bb0)
Location: net/mptcp/pm.c:227
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81c86bb0-ffffffff81c86c8c: mptcp_pm_rm_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2d1c0)
Location: net/mptcp/pm.c:258
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81e2d1c0-ffffffff81e2d2ad: mptcp_pm_rm_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff820055d0)
Location: net/mptcp/pm.c:258
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820055d0-ffffffff820056bd: mptcp_pm_rm_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff820817c0)
Location: net/mptcp/pm.c:275
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820817c0-ffffffff820818ab: mptcp_pm_rm_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_rm_addr_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82156de0)
Location: net/mptcp/pm.c:275
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82156de0-ffffffff82156ecb: mptcp_pm_rm_addr_received (STB_GLOBAL)
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
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mptcp_rm_list *rm_list</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 rm_id</code>
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
