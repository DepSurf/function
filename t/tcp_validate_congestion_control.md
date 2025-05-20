# Function: <code>tcp_validate_congestion_control</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_validate_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81f34655)
Location: net/ipv4/tcp_cong.c:78
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_validate
```
**Symbols:**

```
ffffffff81f345f0-ffffffff81f3463e: tcp_validate_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_validate_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ffa7d5)
Location: net/ipv4/tcp_cong.c:78
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_validate
```
**Symbols:**

```
ffffffff81ffa770-ffffffff81ffa7be: tcp_validate_congestion_control (STB_GLOBAL)
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
