# Function: <code>mptcp_pm_add_addr_echoed</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock *msk, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7720)
Location: net/mptcp/pm.c:200
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb7720-ffffffff81bb77ac: mptcp_pm_add_addr_echoed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock *msk, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:204
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81d43f36-ffffffff81d43f4b: mptcp_pm_add_addr_echoed.cold (STB_LOCAL)
ffffffff81c86aa0-ffffffff81c86b35: mptcp_pm_add_addr_echoed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:235
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81f10ac4-ffffffff81f10ad9: mptcp_pm_add_addr_echoed.cold (STB_LOCAL)
ffffffff81e2d080-ffffffff81e2d128: mptcp_pm_add_addr_echoed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:235
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820b6def-ffffffff820b6e04: mptcp_pm_add_addr_echoed.cold (STB_LOCAL)
ffffffff82005470-ffffffff82005518: mptcp_pm_add_addr_echoed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:252
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff8213814e-ffffffff82138163: mptcp_pm_add_addr_echoed.cold (STB_LOCAL)
ffffffff82081660-ffffffff82081708: mptcp_pm_add_addr_echoed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_add_addr_echoed(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:252
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82219f64-ffffffff82219f79: mptcp_pm_add_addr_echoed.cold (STB_LOCAL)
ffffffff82156c80-ffffffff82156d28: mptcp_pm_add_addr_echoed (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_addr_info *addr</code> ➡️ <code>const struct mptcp_addr_info *addr</code>
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
