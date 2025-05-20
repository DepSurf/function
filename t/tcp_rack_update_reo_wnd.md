# Function: <code>tcp_rack_update_reo_wnd</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff818c1650)
Location: net/ipv4/tcp_recovery.c:182
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818c1650-ffffffff818c16d9: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819171e0)
Location: net/ipv4/tcp_recovery.c:201
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819171e0-ffffffff8191725c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819459f0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819459f0-ffffffff81945a6c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819a9ff0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819a9ff0-ffffffff819aa06c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819e0cb0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819e0cb0-ffffffff819e0d2c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ace2a0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ace2a0-ffffffff81ace31c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ada2b0)
Location: net/ipv4/tcp_recovery.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ada2b0-ffffffff81ada32c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ac5310)
Location: net/ipv4/tcp_recovery.c:190
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ac5310-ffffffff81ac5388: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81b83b20)
Location: net/ipv4/tcp_recovery.c:191
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81b83b20-ffffffff81b83b98: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81d14240)
Location: net/ipv4/tcp_recovery.c:187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81d14240-ffffffff81d142d6: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81eda2b0)
Location: net/ipv4/tcp_recovery.c:187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81eda2b0-ffffffff81eda346: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81f39390)
Location: net/ipv4/tcp_recovery.c:187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f39390-ffffffff81f39426: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81fff480)
Location: net/ipv4/tcp_recovery.c:187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81fff480-ffffffff81fff516: tcp_rack_update_reo_wnd (STB_GLOBAL)
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
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffff800010c94af8)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c94af8-ffff800010c94b9c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c0da33a0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0da33a0-c0da3430: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c000000000da5390)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000da5390-c000000000da5454: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffe0007f3e64)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007f3e64-ffffffe0007f3f20: tcp_rack_update_reo_wnd (STB_GLOBAL)
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
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81980b20)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81980b20-ffffffff81980b9c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8193a5e0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8193a5e0-ffffffff8193a65c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819eb2f0)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819eb2f0-ffffffff819eb36c: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rack_update_reo_wnd(struct sock *sk, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819f5170)
Location: net/ipv4/tcp_recovery.c:202
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819f5170-ffffffff819f51ec: tcp_rack_update_reo_wnd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
