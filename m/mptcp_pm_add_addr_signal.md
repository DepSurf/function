# Function: <code>mptcp_pm_add_addr_signal</code>

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
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_addr_info *saddr, bool *echo, bool *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6c40)
Location: net/mptcp/pm.c:213
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81bc6c40-ffffffff81bc6d28: mptcp_pm_add_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, unsigned int remaining, struct mptcp_addr_info *saddr, bool *echo, bool *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7950)
Location: net/mptcp/pm.c:252
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81bb7950-ffffffff81bb7a2b: mptcp_pm_add_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, struct sk_buff *skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info *addr, bool *echo, bool *port, bool *drop_other_suboptions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:263
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81d43f4b-ffffffff81d43fed: mptcp_pm_add_addr_signal.cold (STB_LOCAL)
ffffffff81c86d40-ffffffff81c86efb: mptcp_pm_add_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, const struct sk_buff *skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info *addr, bool *echo, bool *drop_other_suboptions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:322
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81f10aee-ffffffff81f10b03: mptcp_pm_add_addr_signal.cold (STB_LOCAL)
ffffffff81e2d460-ffffffff81e2d5e5: mptcp_pm_add_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, const struct sk_buff *skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info *addr, bool *echo, bool *drop_other_suboptions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:322
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff820b6e19-ffffffff820b6e2e: mptcp_pm_add_addr_signal.cold (STB_LOCAL)
ffffffff820058b0-ffffffff82005a35: mptcp_pm_add_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, const struct sk_buff *skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info *addr, bool *echo, bool *drop_other_suboptions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:339
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff82138178-ffffffff8213818d: mptcp_pm_add_addr_signal.cold (STB_LOCAL)
ffffffff82081aa0-ffffffff82081c25: mptcp_pm_add_addr_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool mptcp_pm_add_addr_signal(struct mptcp_sock *msk, const struct sk_buff *skb, unsigned int opt_size, unsigned int remaining, struct mptcp_addr_info *addr, bool *echo, bool *drop_other_suboptions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:332
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff82219f8e-ffffffff82219fa3: mptcp_pm_add_addr_signal.cold (STB_LOCAL)
ffffffff82157090-ffffffff82157215: mptcp_pm_add_addr_signal (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff *skb</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opt_size</code>
</li>
<li>
<b>Param added. </b>
<code>struct mptcp_addr_info *addr</code>
</li>
<li>
<b>Param added. </b>
<code>bool *drop_other_suboptions</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mptcp_addr_info *saddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, remaining, saddr, echo, port</code> ➡️ <code>msk, skb, opt_size, remaining, addr, echo, port, drop_other_suboptions</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *port</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, skb, opt_size, remaining, addr, echo, port, drop_other_suboptions</code> ➡️ <code>msk, skb, opt_size, remaining, addr, echo, drop_other_suboptions</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
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
