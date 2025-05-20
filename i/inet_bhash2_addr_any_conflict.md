# Function: <code>inet_bhash2_addr_any_conflict</code>

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
bool inet_bhash2_addr_any_conflict(const struct sock *sk, int port, int l3mdev, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea70a0)
Location: net/ipv4/inet_connection_sock.c:263
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ea70a0-ffffffff81ea71d5: inet_bhash2_addr_any_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_bhash2_addr_any_conflict(const struct sock *sk, int port, int l3mdev, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f05840)
Location: net/ipv4/inet_connection_sock.c:284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f05840-ffffffff81f05975: inet_bhash2_addr_any_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inet_bhash2_addr_any_conflict(const struct sock *sk, int port, int l3mdev, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9b20)
Location: net/ipv4/inet_connection_sock.c:282
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81fc9b20-ffffffff81fc9c56: inet_bhash2_addr_any_conflict (STB_LOCAL)
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
