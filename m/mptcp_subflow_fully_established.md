# Function: <code>mptcp_subflow_fully_established</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mptcp_subflow_fully_established(struct mptcp_subflow_context *subflow, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc1bce)
Location: net/mptcp/subflow.c:524
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
Direct callers:
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bc2fd0-ffffffff81bc2ff6: mptcp_subflow_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mptcp_subflow_fully_established(struct mptcp_subflow_context *subflow, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb251c)
Location: net/mptcp/subflow.c:604
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
Direct callers:
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bb3530-ffffffff81bb3556: mptcp_subflow_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mptcp_subflow_fully_established(struct mptcp_subflow_context *subflow, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c807d1)
Location: net/mptcp/subflow.c:617
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
Direct callers:
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81c81c40-ffffffff81c81c67: mptcp_subflow_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mptcp_subflow_fully_established(struct mptcp_subflow_context *subflow, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e26424)
Location: net/mptcp/subflow.c:663
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
Direct callers:
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81e277b0-ffffffff81e277e3: mptcp_subflow_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_subflow_fully_established(struct mptcp_subflow_context *subflow, const struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffef80)
Location: net/mptcp/subflow.c:727
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81ffef80-ffffffff81fff034: mptcp_subflow_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_subflow_fully_established(struct mptcp_subflow_context *subflow, const struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8207b1a0)
Location: net/mptcp/subflow.c:728
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff8207b1a0-ffffffff8207b254: mptcp_subflow_fully_established (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_options_received *mp_opt</code> ➡️ <code>const struct mptcp_options_received *mp_opt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
