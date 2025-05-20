# Function: <code>inet_bhashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762f97)
Location: include/net/inet_hashtables.h:181
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/inet_hashtables.h:181
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763bdb)
Location: include/net/inet_hashtables.h:181
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf3d0)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf7ee)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d00c5)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ff1c0)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff5de)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817ffef2)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181f436)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f80e)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821003)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189e396)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e77e)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdc3)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2e0a)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f33a7)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4921)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8192098e)
Location: include/net/inet_hashtables.h:210
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920ec7)
Location: include/net/inet_hashtables.h:210
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819226ca)
Location: include/net/inet_hashtables.h:210
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819832d0)
Location: include/net/inet_hashtables.h:206
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983897)
Location: include/net/inet_hashtables.h:206
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984e56)
Location: include/net/inet_hashtables.h:206
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b9b43)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba087)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb8cc)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa44af)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b17)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa73f4)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aaeaff)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf177)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1a84)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a99d3f)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a48a)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ccf3)
Location: include/net/inet_hashtables.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b551af)
Location: include/net/inet_hashtables.h:224
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b558fa)
Location: include/net/inet_hashtables.h:224
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b58a33)
Location: include/net/inet_hashtables.h:224
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2d6d)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce32fa)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce6c56)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea52cb)
Location: include/net/inet_hashtables.h:260
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5b78)
Location: include/net/inet_hashtables.h:260
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea9f1f)
Location: include/net/inet_hashtables.h:260
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f03a5a)
Location: include/net/inet_hashtables.h:260
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f042f9)
Location: include/net/inet_hashtables.h:260
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0878d)
Location: include/net/inet_hashtables.h:260
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc7d01)
Location: include/net/inet_hashtables.h:255
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8649)
Location: include/net/inet_hashtables.h:255
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccaed)
Location: include/net/inet_hashtables.h:255
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6b2f0)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6ba84)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6e444)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7a3f4)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a7d8)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7d0dc)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d70834)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70d84)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d74130)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0ef8)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1470)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d288c)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819599b3)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959ef7)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b73c)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819134a3)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819139e7)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8191522c)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c4183)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c46c7)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5f0c)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cdbf5)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819cdf87)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf9f7)
Location: include/net/inet_hashtables.h:212
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
</ul>

## Differences
