# Function: <code>tcp_rack_detect_loss</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81841a50)
Location: net/ipv4/tcp_recovery.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81841a50-ffffffff81841bdb: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff818c1270)
Location: net/ipv4/tcp_recovery.c:44
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff818c1270-ffffffff818c1418: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81916e10)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81916e10-ffffffff81916f73: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819455f0)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff819455f0-ffffffff8194576b: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819a9bf0)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff819a9bf0-ffffffff819a9d63: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819e08b0)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff819e08b0-ffffffff819e0a23: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81acde30)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81acde30-ffffffff81acdfce: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ad9e90)
Location: net/ipv4/tcp_recovery.c:62
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81ad9e90-ffffffff81ada003: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ac4ee0)
Location: net/ipv4/tcp_recovery.c:62
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81ac4ee0-ffffffff81ac505d: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81b836f0)
Location: net/ipv4/tcp_recovery.c:62
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81b836f0-ffffffff81b8386d: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81d13db0)
Location: net/ipv4/tcp_recovery.c:58
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81d13db0-ffffffff81d13f4b: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ed9dd0)
Location: net/ipv4/tcp_recovery.c:58
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81ed9dd0-ffffffff81ed9f6b: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81f38eb0)
Location: net/ipv4/tcp_recovery.c:58
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81f38eb0-ffffffff81f3904b: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ffef90)
Location: net/ipv4/tcp_recovery.c:58
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81ffef90-ffffffff81fff12b: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffff800010c94670)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffff800010c94670-ffff800010c94814: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c0da2f28)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
c0da2f28-c0da3110: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c000000000da4e20)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
c000000000da4e20-c000000000da503c: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffe0007f3ab8)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffe0007f3ab8-ffffffe0007f3c10: tcp_rack_detect_loss (STB_LOCAL)
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
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81980720)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81980720-ffffffff81980893: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8193a1e0)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff8193a1e0-ffffffff8193a353: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819eaef0)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff819eaef0-ffffffff819eb063: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rack_detect_loss(struct sock *sk, u32 *reo_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819f4d70)
Location: net/ipv4/tcp_recovery.c:76
Inline: False
Direct callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff819f4d70-ffffffff819f4ee3: tcp_rack_detect_loss (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
