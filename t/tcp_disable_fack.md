# Function: <code>tcp_disable_fack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_disable_fack(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176c0ab)
Location: net/ipv4/tcp_input.c:837
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81770c70-ffffffff81770cac: tcp_disable_fack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_disable_fack(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dd84f)
Location: net/ipv4/tcp_input.c:839
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff817dcbe0-ffffffff817dcc1c: tcp_disable_fack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_disable_fack(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180d984)
Location: net/ipv4/tcp_input.c:862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8180cce0-ffffffff8180cd1c: tcp_disable_fack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_disable_fack(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81827d69)
Location: net/ipv4/tcp_input.c:869
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_update_reordering
Direct callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8182cf50-ffffffff8182cf8c: tcp_disable_fack (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
