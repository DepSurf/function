# Function: <code>mptcp_write_options</code>

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
void mptcp_write_options(__be32 *ptr, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb16d0)
Location: net/mptcp/options.c:879
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff81bb16d0-ffffffff81bb19d7: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_write_options(__be32 *ptr, const struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc5610)
Location: net/mptcp/options.c:1072
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff81bc5610-ffffffff81bc599c: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_write_options(__be32 *ptr, const struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb6080)
Location: net/mptcp/options.c:1128
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff81bb6080-ffffffff81bb6511: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_write_options(__be32 *ptr, const struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c84dd0)
Location: net/mptcp/options.c:1242
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff81c84dd0-ffffffff81c8552c: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_write_options(struct tcphdr *th, __be32 *ptr, struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e2ae50)
Location: net/mptcp/options.c:1321
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff81e2ae50-ffffffff81e2b716: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_write_options(struct tcphdr *th, __be32 *ptr, struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82003000)
Location: net/mptcp/options.c:1330
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff82003000-ffffffff820038c6: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_write_options(struct tcphdr *th, __be32 *ptr, struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207f190)
Location: net/mptcp/options.c:1341
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff8207f190-ffffffff8207fa56: mptcp_write_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_write_options(struct tcphdr *th, __be32 *ptr, struct tcp_sock *tp, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82154680)
Location: net/mptcp/options.c:1344
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_options_write
```
**Symbols:**

```
ffffffff82154680-ffffffff82154f45: mptcp_write_options (STB_GLOBAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcp_sock *tp</code>
</li>
<li>
<b>Param reordered. </b>
<code>ptr, opts</code> ➡️ <code>ptr, tp, opts</code>
</li>
</ul>
</details>
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
<code>struct tcphdr *th</code>
</li>
<li>
<b>Param reordered. </b>
<code>ptr, tp, opts</code> ➡️ <code>th, ptr, tp, opts</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct tcp_sock *tp</code> ➡️ <code>struct tcp_sock *tp</code>
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
