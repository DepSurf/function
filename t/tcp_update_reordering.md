# Function: <code>tcp_update_reordering</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176c060)
Location: net/ipv4/tcp_input.c:851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff8176c060-ffffffff8176c0ff: tcp_update_reordering.constprop.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dd81c)
Location: net/ipv4/tcp_input.c:853
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff817d8610-ffffffff817d86b3: tcp_update_reordering.constprop.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180d951)
Location: net/ipv4/tcp_input.c:876
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81808a30-ffffffff81808ad3: tcp_update_reordering.constprop.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_update_reordering(struct sock *sk, const int metric, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81827d50)
Location: net/ipv4/tcp_input.c:883
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81827d50-ffffffff81827df7: tcp_update_reordering (STB_LOCAL)
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
</ul>
