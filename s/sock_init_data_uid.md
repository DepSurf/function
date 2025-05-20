# Function: <code>sock_init_data_uid</code>

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
void sock_init_data_uid(struct socket *sock, struct sock *sk, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9a390)
Location: net/core/sock.c:3384
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
```
**Symbols:**

```
ffffffff81d9a390-ffffffff81d9a68f: sock_init_data_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_init_data_uid(struct socket *sock, struct sock *sk, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e08bf0)
Location: net/core/sock.c:3417
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
```
**Symbols:**

```
ffffffff81e08bf0-ffffffff81e08eef: sock_init_data_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_init_data_uid(struct socket *sock, struct sock *sk, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5660)
Location: net/core/sock.c:3427
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
```
**Symbols:**

```
ffffffff81ec5660-ffffffff81ec595f: sock_init_data_uid (STB_GLOBAL)
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
