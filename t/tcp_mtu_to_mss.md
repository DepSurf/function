# Function: <code>tcp_mtu_to_mss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817750f8)
Location: net/ipv4/tcp_output.c:1318
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff817757b0-ffffffff8177581c: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e3e97)
Location: net/ipv4/tcp_output.c:1333
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff817e2700-ffffffff817e2773: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81814462)
Location: net/ipv4/tcp_output.c:1355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81812d60-ffffffff81812dd3: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81834668)
Location: net/ipv4/tcp_output.c:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81832f90-ffffffff81833003: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b3aae)
Location: net/ipv4/tcp_output.c:1488
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff818b2410-ffffffff818b2485: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81909125)
Location: net/ipv4/tcp_output.c:1479
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81907910-ffffffff81907985: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819372bf)
Location: net/ipv4/tcp_output.c:1467
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81935ba0-ffffffff81935c15: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199bbe1)
Location: net/ipv4/tcp_output.c:1480
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81999f30-ffffffff81999fa5: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d2601)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819d0940-ffffffff819d09b3: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abf361)
Location: net/ipv4/tcp_output.c:1562
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81abdb20-ffffffff81abdb93: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acad4b)
Location: net/ipv4/tcp_output.c:1729
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ac9400-ffffffff81ac9473: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab5d26)
Location: net/ipv4/tcp_output.c:1729
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ab2ef0-ffffffff81ab2f66: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b72d76)
Location: net/ipv4/tcp_output.c:1729
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81b6fd30-ffffffff81b6fda6: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d02474)
Location: net/ipv4/tcp_output.c:1725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81cff400-ffffffff81cff482: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec7654)
Location: net/ipv4/tcp_output.c:1722
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ec4470-ffffffff81ec44f2: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f25f24)
Location: net/ipv4/tcp_output.c:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81f22760-ffffffff81f227e2: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe7529)
Location: net/ipv4/tcp_output.c:1767
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81fe4db0-ffffffff81fe4e05: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c851f0)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffff800010c83570-ffff800010c83600: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d94494)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
c0d92770-c0d92804: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d91248)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
c000000000d8edc0-c000000000d8ee60: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e6b36)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffe0007e5146-ffffffe0007e51c6: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81972471)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819707b0-ffffffff81970823: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192bf41)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff8192a280-ffffffff8192a2f3: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dcc41)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819daf80-ffffffff819daff3: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_mtu_to_mss(struct sock *sk, int pmtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e68c1)
Location: net/ipv4/tcp_output.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819e4c00-ffffffff819e4c73: tcp_mtu_to_mss (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
