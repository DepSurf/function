# Function: <code>bictcp_acked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bictcp_acked(struct sock *sk, u32 cnt, s32 rtt_us);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff817aca00)
Location: net/ipv4/tcp_cubic.c:440
Inline: True
```
**Symbols:**

```
ffffffff817aca00-ffffffff817acc13: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81819960)
Location: net/ipv4/tcp_cubic.c:440
Inline: False
```
**Symbols:**

```
ffffffff81819960-ffffffff81819b77: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8184b220)
Location: net/ipv4/tcp_cubic.c:440
Inline: False
```
**Symbols:**

```
ffffffff8184b220-ffffffff8184b437: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8186eca0)
Location: net/ipv4/tcp_cubic.c:440
Inline: False
```
**Symbols:**

```
ffffffff8186eca0-ffffffff8186eea9: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff818ef630)
Location: net/ipv4/tcp_cubic.c:429
Inline: False
```
**Symbols:**

```
ffffffff818ef630-ffffffff818ef839: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81945f90)
Location: net/ipv4/tcp_cubic.c:429
Inline: False
```
**Symbols:**

```
ffffffff81945f90-ffffffff81946198: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81976130)
Location: net/ipv4/tcp_cubic.c:429
Inline: False
```
**Symbols:**

```
ffffffff81976130-ffffffff81976338: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff819dfcb0)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffff819dfcb0-ffffffff819dfebf: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81a16ca0)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffff81a16ca0-ffffffff81a16eaf: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b07f70)
Location: net/ipv4/tcp_cubic.c:454
Inline: False
```
**Symbols:**

```
ffffffff81b07f70-ffffffff81b07fea: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b16350)
Location: net/ipv4/tcp_cubic.c:454
Inline: False
```
**Symbols:**

```
ffffffff81b16350-ffffffff81b163ca: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffff800010cd2e00)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffff800010cd2e00-ffff800010cd3060: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (c0ddc988)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
c0ddc988-c0ddcbd4: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (c000000000df0fa0)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
c000000000df0fa0-c000000000df12e8: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffe000823be2)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffe000823be2-ffffffe000823e18: bictcp_acked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff819b6330)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffff819b6330-ffffffff819b653f: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81973120)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffff81973120-ffffffff8197332f: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81a20db0)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffff81a20db0-ffffffff81a20fbf: bictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81a2c110)
Location: net/ipv4/tcp_cubic.c:430
Inline: False
```
**Symbols:**

```
ffffffff81a2c110-ffffffff81a2c309: bictcp_acked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct ack_sample *sample</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 cnt</code>
</li>
<li>
<b>Param removed. </b>
<code>s32 rtt_us</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
