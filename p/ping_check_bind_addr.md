# Function: <code>ping_check_bind_addr</code>

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
In net/ipv4/ping.c (ffffffff817a29bc)
Location: net/ipv4/ping.c:302
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff8181128f)
Location: net/ipv4/ping.c:304
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff8184279f)
Location: net/ipv4/ping.c:299
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff81864001)
Location: net/ipv4/ping.c:300
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff818e4141)
Location: net/ipv4/ping.c:300
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff8193aa07)
Location: net/ipv4/ping.c:300
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff8196a6f7)
Location: net/ipv4/ping.c:300
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff819d13a7)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff81a07f07)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af6880)
Location: net/ipv4/ping.c:295
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81af6880-ffffffff81af6b0b: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81b03700)
Location: net/ipv4/ping.c:295
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81b03700-ffffffff81b03992: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81aeef40)
Location: net/ipv4/ping.c:295
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81aeef40-ffffffff81aef1b4: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81baf310)
Location: net/ipv4/ping.c:302
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81baf310-ffffffff81baf581: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81d42680)
Location: net/ipv4/ping.c:299
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81d42680-ffffffff81d428fe: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f0b530)
Location: net/ipv4/ping.c:318
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81f0b530-ffffffff81f0b7b9: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f6b110)
Location: net/ipv4/ping.c:308
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff81f6b110-ffffffff81f6b399: ping_check_bind_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ping_check_bind_addr(struct sock *sk, struct inet_sock *isk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff82031c00)
Location: net/ipv4/ping.c:308
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_bind
```
**Symbols:**

```
ffffffff82031c00-ffffffff82031ea6: ping_check_bind_addr (STB_LOCAL)
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
In net/ipv4/ping.c (ffff800010cc1160)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (c0dcce78)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (c000000000ddc3e4)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffe000816142)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff819a7ca7)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff81961767)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff81a12547)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
In net/ipv4/ping.c (ffffffff81a1cf46)
Location: net/ipv4/ping.c:295
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
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
