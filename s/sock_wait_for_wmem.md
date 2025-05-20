# Function: <code>sock_wait_for_wmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8170263d)
Location: net/core/sock.c:1812
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176986d)
Location: net/core/sock.c:1841
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff8179678d)
Location: net/core/sock.c:1839
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff817b4b5d)
Location: net/core/sock.c:1978
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff8182cd9c)
Location: net/core/sock.c:2016
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81876c0e)
Location: net/core/sock.c:2036
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff818973de)
Location: net/core/sock.c:2032
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff818e1821)
Location: net/core/sock.c:2173
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81913a13)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int sock_wait_for_wmem(struct sock *sk, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e51b0)
Location: net/core/sock.c:2297
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
**Symbols:**

```
ffffffff819e51b0-ffffffff819e52bd: sock_wait_for_wmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sock_wait_for_wmem(struct sock *sk, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4af0)
Location: net/core/sock.c:2289
Inline: False
Direct callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
**Symbols:**

```
ffffffff819e4af0-ffffffff819e4c08: sock_wait_for_wmem (STB_LOCAL)
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
In net/core/sock.c (ffffffff819cb513)
Location: net/core/sock.c:2312
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81a7aba3)
Location: net/core/sock.c:2436
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81beeac7)
Location: net/core/sock.c:2605
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81d9b117)
Location: net/core/sock.c:2684
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81e0a301)
Location: net/core/sock.c:2744
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81ec6cf3)
Location: net/core/sock.c:2724
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffff800010bab470)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (c0cca054)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (c000000000c81d44)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffe00073ed38)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff818b3a13)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff8186d963)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81904a13)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
In net/core/sock.c (ffffffff81925ab3)
Location: net/core/sock.c:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
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
