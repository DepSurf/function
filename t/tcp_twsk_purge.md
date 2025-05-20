# Function: <code>tcp_twsk_purge</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_twsk_purge(struct list_head *net_exit_list, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:367
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit_batch
```
**Symbols:**

```
ffffffff820afc91-ffffffff820afca6: tcp_twsk_purge.cold (STB_LOCAL)
ffffffff81ed3830-ffffffff81ed38e9: tcp_twsk_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_twsk_purge(struct list_head *net_exit_list, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:367
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit_batch
```
**Symbols:**

```
ffffffff82130fae-ffffffff82130fc3: tcp_twsk_purge.cold (STB_LOCAL)
ffffffff81f32820-ffffffff81f328d9: tcp_twsk_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_twsk_purge(struct list_head *net_exit_list, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:391
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit_batch
```
**Symbols:**

```
ffffffff8221292a-ffffffff8221293f: tcp_twsk_purge.cold (STB_LOCAL)
ffffffff81ff88e0-ffffffff81ff8999: tcp_twsk_purge (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
