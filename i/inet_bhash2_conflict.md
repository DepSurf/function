# Function: <code>inet_bhash2_conflict</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inet_bhash2_conflict(const struct sock *sk, const struct inet_bind2_bucket *tb2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6f20)
Location: net/ipv4/inet_connection_sock.c:187
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
```
**Symbols:**

```
ffffffff81ea6f20-ffffffff81ea708a: inet_bhash2_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_bhash2_conflict(const struct sock *sk, const struct inet_bind2_bucket *tb2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f056f0)
Location: net/ipv4/inet_connection_sock.c:208
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
```
**Symbols:**

```
ffffffff81f056f0-ffffffff81f05827: inet_bhash2_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9a60)
Location: net/ipv4/inet_connection_sock.c:213
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
```
**Symbols:**

```
ffffffff81fc9a60-ffffffff81fc9b0f: inet_bhash2_conflict.isra.0 (STB_LOCAL)
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
</ul>
