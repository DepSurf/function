# Function: <code>tcp_zerocopy_receive</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f7d0e)
Location: net/ipv4/tcp.c:1751
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81924a55)
Location: net/ipv4/tcp.c:1747
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81987e70)
Location: net/ipv4/tcp.c:1737
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bf279)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa9950)
Location: net/ipv4/tcp.c:1775
Inline: False
```
**Symbols:**

```
ffffffff81aa9950-ffffffff81aa9fc2: tcp_zerocopy_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab6d30)
Location: net/ipv4/tcp.c:2008
Inline: False
```
**Symbols:**

```
ffffffff81ab6d30-ffffffff81ab74dc: tcp_zerocopy_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa1f20)
Location: net/ipv4/tcp.c:2059
Inline: False
```
**Symbols:**

```
ffffffff81aa1f20-ffffffff81aa26c3: tcp_zerocopy_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2059
Inline: False
```
**Symbols:**

```
ffffffff81b5dce0-ffffffff81b5e4db: tcp_zerocopy_receive (STB_LOCAL)
ffffffff81d3a58c-ffffffff81d3a5ac: tcp_zerocopy_receive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2086
Inline: False
```
**Symbols:**

```
ffffffff81cec6b0-ffffffff81cece8a: tcp_zerocopy_receive (STB_LOCAL)
ffffffff81f06db3-ffffffff81f06dd4: tcp_zerocopy_receive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2186
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff81eb05c0-ffffffff81eb0d8c: tcp_zerocopy_receive (STB_LOCAL)
ffffffff820ae921-ffffffff820ae942: tcp_zerocopy_receive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2070
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff81f0ea70-ffffffff81f0f403: tcp_zerocopy_receive (STB_LOCAL)
ffffffff8212fdb8-ffffffff8212fded: tcp_zerocopy_receive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_zerocopy_receive(struct sock *sk, struct tcp_zerocopy_receive *zc, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2077
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff81fd2be0-ffffffff81fd35f5: tcp_zerocopy_receive (STB_LOCAL)
ffffffff82211aa4-ffffffff82211ad9: tcp_zerocopy_receive.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c7368c)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d81e4c)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d790b4)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d55b6)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195f0e9)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81918bd9)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c98b9)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d3409)
Location: net/ipv4/tcp.c:1738
Inline: True
```
</details>
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
<code>struct scm_timestamping_internal *tss</code>
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
