# Function: <code>tcp_fetch_timewait_stamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_fetch_timewait_stamp(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81781f00)
Location: net/ipv4/tcp_metrics.c:610
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
**Symbols:**

```
ffffffff81781f00-ffffffff81781f4a: tcp_fetch_timewait_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_fetch_timewait_stamp(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817ef3c0)
Location: net/ipv4/tcp_metrics.c:611
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
**Symbols:**

```
ffffffff817ef3c0-ffffffff817ef40a: tcp_fetch_timewait_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_fetch_timewait_stamp(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8181fc10)
Location: net/ipv4/tcp_metrics.c:610
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
**Symbols:**

```
ffffffff8181fc10-ffffffff8181fc5a: tcp_fetch_timewait_stamp (STB_GLOBAL)
```
</details>
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
</ul>
