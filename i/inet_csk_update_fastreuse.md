# Function: <code>inet_csk_update_fastreuse</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa71a0)
Location: net/ipv4/inet_connection_sock.c:299
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81aa71a0-ffffffff81aa72fa: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1830)
Location: net/ipv4/inet_connection_sock.c:299
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ab1830-ffffffff81ab198a: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9caa0)
Location: net/ipv4/inet_connection_sock.c:299
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81a9caa0-ffffffff81a9cbfa: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:307
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81d3a2a4-ffffffff81d3a2c1: inet_csk_update_fastreuse.cold (STB_LOCAL)
ffffffff81b587d0-ffffffff81b5893f: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:311
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f06a2f-ffffffff81f06a4c: inet_csk_update_fastreuse.cold (STB_LOCAL)
ffffffff81ce69b0-ffffffff81ce6b33: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:431
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff820ae665-ffffffff820ae682: inet_csk_update_fastreuse.cold (STB_LOCAL)
ffffffff81ea9c20-ffffffff81ea9da3: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:452
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8212fb2b-ffffffff8212fb48: inet_csk_update_fastreuse.cold (STB_LOCAL)
ffffffff81f08480-ffffffff81f08603: inet_csk_update_fastreuse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void inet_csk_update_fastreuse(struct inet_bind_bucket *tb, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:450
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff822118be-ffffffff822118db: inet_csk_update_fastreuse.cold (STB_LOCAL)
ffffffff81fcc7e0-ffffffff81fcc963: inet_csk_update_fastreuse (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
