# Function: <code>tcp_tw_remember_stamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tcp_tw_remember_stamp(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81782340)
Location: net/ipv4/tcp_metrics.c:659
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81782340-ffffffff817824e2: tcp_tw_remember_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tcp_tw_remember_stamp(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817ef800)
Location: net/ipv4/tcp_metrics.c:660
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff817ef800-ffffffff817ef9a2: tcp_tw_remember_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_tw_remember_stamp(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81820210)
Location: net/ipv4/tcp_metrics.c:659
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81820210-ffffffff818203b2: tcp_tw_remember_stamp (STB_GLOBAL)
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
