# Function: <code>inet_ehash_bucket</code>

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
In net/ipv4/inet_hashtables.c (ffffffff817621d0)
Location: include/net/inet_hashtables.h:152
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8176332b)
Location: include/net/inet_hashtables.h:152
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8180236b)
Location: include/net/inet_hashtables.h:152
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff817cef32)
Location: include/net/inet_hashtables.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf7eb)
Location: include/net/inet_hashtables.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187361a)
Location: include/net/inet_hashtables.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff817fed45)
Location: include/net/inet_hashtables.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff5db)
Location: include/net/inet_hashtables.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7c8a)
Location: include/net/inet_hashtables.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff8181f058)
Location: include/net/inet_hashtables.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f80b)
Location: include/net/inet_hashtables.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce50a)
Location: include/net/inet_hashtables.h:156
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff8189e014)
Location: include/net/inet_hashtables.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e77b)
Location: include/net/inet_hashtables.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819533db)
Location: include/net/inet_hashtables.h:156
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff818f295a)
Location: include/net/inet_hashtables.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f338b)
Location: include/net/inet_hashtables.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ace0c)
Location: include/net/inet_hashtables.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819203ca)
Location: include/net/inet_hashtables.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920eab)
Location: include/net/inet_hashtables.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e37d1)
Location: include/net/inet_hashtables.h:170
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81982cea)
Location: include/net/inet_hashtables.h:166
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8198387b)
Location: include/net/inet_hashtables.h:166
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a524e6)
Location: include/net/inet_hashtables.h:166
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819b954a)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba068)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a890f6)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81aa4079)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4af8)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84226)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81aae6a4)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf158)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93a8c)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81a99784)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a46b)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82b9c)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81b54c04)
Location: include/net/inet_hashtables.h:178
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b558db)
Location: include/net/inet_hashtables.h:178
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ec6c)
Location: include/net/inet_hashtables.h:178
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ce27f4)
Location: include/net/inet_hashtables.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce32db)
Location: include/net/inet_hashtables.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def629)
Location: include/net/inet_hashtables.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ea3c4d)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5b52)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc36f9)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81f024cd)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f042d2)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024539)
Location: include/net/inet_hashtables.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81fc688d)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8622)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3849)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffff800010c6ac4c)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6ba6c)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55ef0)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (c0d79cf4)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a780)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (c0e564a4)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (c000000000d6ff38)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70d50)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8ef9c)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffe0007d0970)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d147e)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d792)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819593ba)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959ed8)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28786)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81912eaa)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819139c8)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5546)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819c3b8a)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c46a8)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94336)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819cd5da)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819cdf6d)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0488)
Location: include/net/inet_hashtables.h:172
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
</li>
</ul>

## Differences
