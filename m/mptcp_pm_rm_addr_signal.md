# Function: <code>mptcp_pm_rm_addr_signal</code>

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
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, u8 *rm_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6d30)
Location: net/mptcp/pm.c:239
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bc6d30-ffffffff81bc6d99: mptcp_pm_rm_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7a30)
Location: net/mptcp/pm.c:278
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bb7a30-ffffffff81bb7aca: mptcp_pm_rm_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86f00)
Location: net/mptcp/pm.c:309
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81c86f00-ffffffff81c86fa2: mptcp_pm_rm_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2d5f0)
Location: net/mptcp/pm.c:369
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81e2d5f0-ffffffff81e2d697: mptcp_pm_rm_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82005a50)
Location: net/mptcp/pm.c:369
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82005a50-ffffffff82005af7: mptcp_pm_rm_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82081c40)
Location: net/mptcp/pm.c:386
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82081c40-ffffffff82081ce9: mptcp_pm_rm_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_pm_rm_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82157230)
Location: net/mptcp/pm.c:379
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82157230-ffffffff821572d9: mptcp_pm_rm_addr_signal (STB_GLOBAL)
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
<code>struct mptcp_rm_list *rm_list</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *rm_id</code>
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
