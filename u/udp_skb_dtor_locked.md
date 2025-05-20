# Function: <code>udp_skb_dtor_locked</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81845a90)
Location: net/ipv4/udp.c:1249
Inline: False
```
**Symbols:**

```
ffffffff81845a90-ffffffff81845aba: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c54d0)
Location: net/ipv4/udp.c:1256
Inline: False
```
**Symbols:**

```
ffffffff818c54d0-ffffffff818c54fa: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191d7c0)
Location: net/ipv4/udp.c:1326
Inline: False
```
**Symbols:**

```
ffffffff8191d7c0-ffffffff8191d7ea: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194c740)
Location: net/ipv4/udp.c:1394
Inline: False
```
**Symbols:**

```
ffffffff8194c740-ffffffff8194c76a: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0ee0)
Location: net/ipv4/udp.c:1381
Inline: False
```
**Symbols:**

```
ffffffff819b0ee0-ffffffff819b0f0a: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e79f0)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffffffff819e79f0-ffffffff819e7a1a: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad429d)
Location: net/ipv4/udp.c:1422
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae080d)
Location: net/ipv4/udp.c:1472
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
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
In net/ipv4/udp.c (ffffffff81acc7f9)
Location: net/ipv4/udp.c:1491
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
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
In net/ipv4/udp.c (ffffffff81b8b089)
Location: net/ipv4/udp.c:1492
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
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
In net/ipv4/udp.c (ffffffff81d1ae87)
Location: net/ipv4/udp.c:1492
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
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
In net/ipv4/udp.c (ffffffff81ee2427)
Location: net/ipv4/udp.c:1503
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
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
In net/ipv4/udp.c (ffffffff81f41f27)
Location: net/ipv4/udp.c:1475
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
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
In net/ipv4/udp.c (ffffffff82007db7)
Location: net/ipv4/udp.c:1450
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b908)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffff800010c9b908-ffff800010c9b950: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da75d4)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
c0da75d4-c0da7604: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daaff0)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
c000000000daaff0-c000000000dab020: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f9c28)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffffffe0007f9c28-ffffffe0007f9c64: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81987860)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffffffff81987860-ffffffff8198788a: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81941320)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffffffff81941320-ffffffff8194134a: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f2030)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffffffff819f2030-ffffffff819f205a: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void udp_skb_dtor_locked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f91b0)
Location: net/ipv4/udp.c:1416
Inline: False
```
**Symbols:**

```
ffffffff819f91b0-ffffffff819f91da: udp_skb_dtor_locked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
