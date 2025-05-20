# Function: <code>tcpm_new</code>

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
In net/ipv4/tcp_metrics.c (ffffffff81781d14)
Location: net/ipv4/tcp_metrics.c:151
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff817ef1d5)
Location: net/ipv4/tcp_metrics.c:151
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff8181fa25)
Location: net/ipv4/tcp_metrics.c:151
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8183f6cb)
Location: net/ipv4/tcp_metrics.c:147
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff818bf9ab)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819155a2)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff81943d52)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff819a8177)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff819de46a)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcp_metrics_block *tcpm_new(struct dst_entry *dst, struct inetpeer_addr *saddr, struct inetpeer_addr *daddr, unsigned int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81acc060)
Location: net/ipv4/tcp_metrics.c:146
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
**Symbols:**

```
ffffffff81acc060-ffffffff81acc21c: tcpm_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcp_metrics_block *tcpm_new(struct dst_entry *dst, struct inetpeer_addr *saddr, struct inetpeer_addr *daddr, unsigned int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ad8020)
Location: net/ipv4/tcp_metrics.c:146
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
**Symbols:**

```
ffffffff81ad8020-ffffffff81ad81dc: tcpm_new (STB_LOCAL)
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
In net/ipv4/tcp_metrics.c (ffffffff81ac3421)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff81b81923)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff81d11d5c)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff81ed7b2c)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff81f3678c)
Location: net/ipv4/tcp_metrics.c:163
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcp_metrics_block *tcpm_new(struct dst_entry *dst, struct inetpeer_addr *saddr, struct inetpeer_addr *daddr, unsigned int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ffc1c0)
Location: net/ipv4/tcp_metrics.c:163
Inline: False
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
**Symbols:**

```
ffffffff81ffc1c0-ffffffff81ffc39d: tcpm_new (STB_LOCAL)
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
In net/ipv4/tcp_metrics.c (ffff800010c92888)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (c0da12f4)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (c000000000da1960)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffe0007f1706)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff8197e2da)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff81937d9a)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff819e8aaa)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
In net/ipv4/tcp_metrics.c (ffffffff819f280a)
Location: net/ipv4/tcp_metrics.c:146
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
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
</ul>
