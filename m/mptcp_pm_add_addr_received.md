# Function: <code>mptcp_pm_add_addr_received</code>

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
void mptcp_pm_add_addr_received(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb2750)
Location: net/mptcp/pm.c:132
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb2750-ffffffff81bb2804: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_add_addr_received(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6a50)
Location: net/mptcp/pm.c:171
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bc6a50-ffffffff81bc6b55: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_add_addr_received(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7620)
Location: net/mptcp/pm.c:178
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb7620-ffffffff81bb7714: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_received(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:180
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81d43f04-ffffffff81d43f36: mptcp_pm_add_addr_received.cold (STB_LOCAL)
ffffffff81c86970-ffffffff81c86a92: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_received(const struct sock *ssk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:202
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81f10a91-ffffffff81f10ac4: mptcp_pm_add_addr_received.cold (STB_LOCAL)
ffffffff81e2cf20-ffffffff81e2d07f: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_received(const struct sock *ssk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:202
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820b6dbc-ffffffff820b6def: mptcp_pm_add_addr_received.cold (STB_LOCAL)
ffffffff82005300-ffffffff8200545a: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_received(const struct sock *ssk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:219
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff8213811b-ffffffff8213814e: mptcp_pm_add_addr_received.cold (STB_LOCAL)
ffffffff820814f0-ffffffff8208164a: mptcp_pm_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_received(const struct sock *ssk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:219
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82219f31-ffffffff82219f64: mptcp_pm_add_addr_received.cold (STB_LOCAL)
ffffffff82156b10-ffffffff82156c6a: mptcp_pm_add_addr_received (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *ssk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mptcp_sock *msk</code>
</li>
</ul>
</details>
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
