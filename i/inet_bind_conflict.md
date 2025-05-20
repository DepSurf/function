# Function: <code>inet_bind_conflict</code>

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
bool inet_bind_conflict(const struct sock *sk, struct sock *sk2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea67f0)
Location: net/ipv4/inet_connection_sock.c:146
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bhash2_conflict
  - net/ipv4/inet_connection_sock.c:inet_bhash2_conflict
```
**Symbols:**

```
ffffffff81ea67f0-ffffffff81ea68f8: inet_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_bind_conflict(const struct sock *sk, struct sock *sk2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f04fc0)
Location: net/ipv4/inet_connection_sock.c:167
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bhash2_conflict
  - net/ipv4/inet_connection_sock.c:inet_bhash2_conflict
```
**Symbols:**

```
ffffffff81f04fc0-ffffffff81f050c8: inet_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inet_bind_conflict(const struct sock *sk, struct sock *sk2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9310)
Location: net/ipv4/inet_connection_sock.c:172
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
```
**Symbols:**

```
ffffffff81fc9310-ffffffff81fc9418: inet_bind_conflict (STB_LOCAL)
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
