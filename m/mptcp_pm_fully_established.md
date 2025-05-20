# Function: <code>mptcp_pm_fully_established</code>

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
void mptcp_pm_fully_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb25d0)
Location: net/mptcp/pm.c:86
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb25d0-ffffffff81bb2655: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc68c0)
Location: net/mptcp/pm.c:119
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bc68c0-ffffffff81bc6956: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7460)
Location: net/mptcp/pm.c:124
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bb7460-ffffffff81bb752d: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:126
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81d43ec8-ffffffff81d43edc: mptcp_pm_fully_established.cold (STB_LOCAL)
ffffffff81c867a0-ffffffff81c8687a: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:129
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81f10a06-ffffffff81f10a1b: mptcp_pm_fully_established.cold (STB_LOCAL)
ffffffff81e2cc40-ffffffff81e2cd2e: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:129
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff820b6d31-ffffffff820b6d46: mptcp_pm_fully_established.cold (STB_LOCAL)
ffffffff82004fe0-ffffffff820050ce: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk, const struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:138
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff821380c7-ffffffff821380dc: mptcp_pm_fully_established.cold (STB_LOCAL)
ffffffff820811d0-ffffffff820812b7: mptcp_pm_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_fully_established(struct mptcp_sock *msk, const struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:138
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff82219edd-ffffffff82219ef2: mptcp_pm_fully_established.cold (STB_LOCAL)
ffffffff821567f0-ffffffff821568d7: mptcp_pm_fully_established (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *ssk</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
