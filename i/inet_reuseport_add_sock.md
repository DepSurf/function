# Function: <code>inet_reuseport_add_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf1b4)
Location: net/ipv4/inet_hashtables.c:435
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fefce)
Location: net/ipv4/inet_hashtables.c:437
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181f277)
Location: net/ipv4/inet_hashtables.c:434
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189e1e7)
Location: net/ipv4/inet_hashtables.c:441
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2c00)
Location: net/ipv4/inet_hashtables.c:555
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81920670)
Location: net/ipv4/inet_hashtables.c:519
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81982faa)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b9813)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_reuseport_add_sock(struct sock *sk, struct inet_listen_hashbucket *ilb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa2e30)
Location: net/ipv4/inet_hashtables.c:516
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81aa2e30-ffffffff81aa2efb: inet_reuseport_add_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_reuseport_add_sock(struct sock *sk, struct inet_listen_hashbucket *ilb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aad1b0)
Location: net/ipv4/inet_hashtables.c:608
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81aad1b0-ffffffff81aad27b: inet_reuseport_add_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a99b23)
Location: net/ipv4/inet_hashtables.c:608
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54f90)
Location: net/ipv4/inet_hashtables.c:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2b6c)
Location: net/ipv4/inet_hashtables.c:568
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea4055)
Location: net/ipv4/inet_hashtables.c:697
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f028b0)
Location: net/ipv4/inet_hashtables.c:684
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc6be6)
Location: net/ipv4/inet_hashtables.c:705
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6afd8)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7a068)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d703a0)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0cb8)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959683)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81913173)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3e53)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cd8ae)
Location: net/ipv4/inet_hashtables.c:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
