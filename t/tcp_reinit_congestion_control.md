# Function: <code>tcp_reinit_congestion_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81780c85)
Location: net/ipv4/tcp_cong.c:194
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff817ee175)
Location: net/ipv4/tcp_cong.c:194
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8181eb38)
Location: net/ipv4/tcp_cong.c:195
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8183ee30)
Location: net/ipv4/tcp_cong.c:192
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff8183ee30-ffffffff8183ee9d: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff818be660)
Location: net/ipv4/tcp_cong.c:189
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff818be660-ffffffff818be6cd: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81914250)
Location: net/ipv4/tcp_cong.c:189
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81914250-ffffffff819142bd: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81942a00)
Location: net/ipv4/tcp_cong.c:189
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81942a00-ffffffff81942a6d: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819a6fd0)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff819a6fd0-ffffffff819a7046: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819ddca0)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff819ddca0-ffffffff819ddd16: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81acaf60)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81acaf60-ffffffff81acb021: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ad7392)
Location: net/ipv4/tcp_cong.c:191
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ac2482)
Location: net/ipv4/tcp_cong.c:191
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81b801f6)
Location: net/ipv4/tcp_cong.c:191
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81d105dd)
Location: net/ipv4/tcp_cong.c:201
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ed62fd)
Location: net/ipv4/tcp_cong.c:201
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81f3521d)
Location: net/ipv4/tcp_cong.c:253
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ffb39d)
Location: net/ipv4/tcp_cong.c:253
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
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
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffff800010c91190)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffff800010c91190-ffff800010c91208: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c0d9fdf8)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
c0d9fdf8-c0d9fe50: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c000000000da0840)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
c000000000da0840-c000000000da08dc: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffe0007f0f76)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffe0007f0f76-ffffffe0007f0fe0: tcp_reinit_congestion_control (STB_LOCAL)
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
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8197db10)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff8197db10-ffffffff8197db86: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819375d0)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff819375d0-ffffffff81937646: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819e82e0)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff819e82e0-ffffffff819e8356: tcp_reinit_congestion_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock *sk, const struct tcp_congestion_ops *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819f2010)
Location: net/ipv4/tcp_cong.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff819f2010-ffffffff819f2086: tcp_reinit_congestion_control (STB_LOCAL)
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
