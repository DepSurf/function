# Function: <code>tcp_get_metrics</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81781c30)
Location: net/ipv4/tcp_metrics.c:318
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
**Symbols:**

```
ffffffff81781c30-ffffffff81781ef7: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817ef0f0)
Location: net/ipv4/tcp_metrics.c:318
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff817ef0f0-ffffffff817ef3bb: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8181f940)
Location: net/ipv4/tcp_metrics.c:318
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff8181f940-ffffffff8181fc0b: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8183f5b0)
Location: net/ipv4/tcp_metrics.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff8183f5b0-ffffffff8183f890: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff818bf890)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff818bf890-ffffffff818bfb70: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81915470)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81915470-ffffffff8191572d: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81943c20)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81943c20-ffffffff81943edd: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819a8050)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff819a8050-ffffffff819a8317: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819de340)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff819de340-ffffffff819de60a: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81acc5a0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81acc5a0-ffffffff81acc71f: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ad8570)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81ad8570-ffffffff81ad86ef: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ac3300)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81ac3300-ffffffff81ac35fd: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81b817f0-ffffffff81b81b03: tcp_get_metrics (STB_LOCAL)
ffffffff81d3bddd-ffffffff81d3bdfd: tcp_get_metrics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81d11bf0-ffffffff81d11f48: tcp_get_metrics (STB_LOCAL)
ffffffff81f08600-ffffffff81f08621: tcp_get_metrics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81ed79c0-ffffffff81ed7d18: tcp_get_metrics (STB_LOCAL)
ffffffff820b00a1-ffffffff820b00c2: tcp_get_metrics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:291
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81f36620-ffffffff81f3697a: tcp_get_metrics (STB_LOCAL)
ffffffff82131314-ffffffff82131335: tcp_get_metrics.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:291
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81ffc8c0-ffffffff81ffca9e: tcp_get_metrics (STB_LOCAL)
ffffffff82212c5b-ffffffff82212c79: tcp_get_metrics.cold (STB_LOCAL)
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
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffff800010c92790)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffff800010c92790-ffff800010c92a88: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (c0da11b4)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
c0da11b4-c0da1464: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (c000000000da17c0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
c000000000da17c0-c000000000da1b04: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffe0007f15fa)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffe0007f15fa-ffffffe0007f1866: tcp_get_metrics (STB_LOCAL)
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
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8197e1b0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff8197e1b0-ffffffff8197e47a: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81937c70)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff81937c70-ffffffff81937f3a: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819e8980)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff819e8980-ffffffff819e8c4a: tcp_get_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcp_metrics_block *tcp_get_metrics(struct sock *sk, struct dst_entry *dst, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819f26e0)
Location: net/ipv4/tcp_metrics.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
**Symbols:**

```
ffffffff819f26e0-ffffffff819f29aa: tcp_get_metrics (STB_LOCAL)
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
