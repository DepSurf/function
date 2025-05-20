# Function: <code>raw_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81784cd0)
Location: net/ipv4/raw.c:486
Inline: False
```
**Symbols:**

```
ffffffff81784cd0-ffffffff817857ed: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817f22d0)
Location: net/ipv4/raw.c:488
Inline: False
```
**Symbols:**

```
ffffffff817f22d0-ffffffff817f2dd3: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818230b0)
Location: net/ipv4/raw.c:490
Inline: False
```
**Symbols:**

```
ffffffff818230b0-ffffffff81823bb9: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81843be0)
Location: net/ipv4/raw.c:496
Inline: False
```
**Symbols:**

```
ffffffff81843be0-ffffffff8184477d: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818c3500)
Location: net/ipv4/raw.c:502
Inline: False
```
**Symbols:**

```
ffffffff818c3500-ffffffff818c40b7: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:502
Inline: False
```
**Symbols:**

```
ffffffff81919170-ffffffff81919d49: raw_sendmsg (STB_LOCAL)
ffffffff8191a5c5-ffffffff8191a620: raw_sendmsg.cold.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:502
Inline: False
```
**Symbols:**

```
ffffffff81947940-ffffffff819485b4: raw_sendmsg (STB_LOCAL)
ffffffff81948e1a-ffffffff81948e67: raw_sendmsg.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff819ac6b0-ffffffff819ace58: raw_sendmsg (STB_LOCAL)
ffffffff819ad481-ffffffff819ad4ce: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff819e3260-ffffffff819e3a0c: raw_sendmsg (STB_LOCAL)
ffffffff819e412e-ffffffff819e417b: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff81ad0b40-ffffffff81ad12ac: raw_sendmsg (STB_LOCAL)
ffffffff81ad186e-ffffffff81ad18bb: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:499
Inline: False
```
**Symbols:**

```
ffffffff81adca80-ffffffff81add29f: raw_sendmsg (STB_LOCAL)
ffffffff81c327a7-ffffffff81c327f4: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:499
Inline: False
```
**Symbols:**

```
ffffffff81ac7af0-ffffffff81ac8333: raw_sendmsg (STB_LOCAL)
ffffffff81c24a79-ffffffff81c24ac6: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:499
Inline: False
```
**Symbols:**

```
ffffffff81b86350-ffffffff81b86bac: raw_sendmsg (STB_LOCAL)
ffffffff81d3bed5-ffffffff81d3bf4d: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:471
Inline: False
```
**Symbols:**

```
ffffffff81d16ca0-ffffffff81d17805: raw_sendmsg (STB_LOCAL)
ffffffff81f086f2-ffffffff81f08786: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:471
Inline: False
```
**Symbols:**

```
ffffffff81edd470-ffffffff81ede0bd: raw_sendmsg (STB_LOCAL)
ffffffff820b01d3-ffffffff820b0210: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:472
Inline: False
```
**Symbols:**

```
ffffffff81f3c6c0-ffffffff81f3d3b1: raw_sendmsg (STB_LOCAL)
ffffffff8213145f-ffffffff8213149c: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:474
Inline: False
```
**Symbols:**

```
ffffffff820027f0-ffffffff82003512: raw_sendmsg (STB_LOCAL)
ffffffff82212da3-ffffffff82212de0: raw_sendmsg.cold (STB_LOCAL)
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
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffff800010c97f08)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffff800010c97f08-ffff800010c9848c: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c0da5d64)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
c0da5d64-c0da6354: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c000000000da9150)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
c000000000da9150-c000000000da98c8: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffe0007f62b0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffe0007f62b0-ffffffe0007f674c: raw_sendmsg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff819830d0-ffffffff8198387c: raw_sendmsg (STB_LOCAL)
ffffffff81983f9e-ffffffff81983feb: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff8193cb90-ffffffff8193d33c: raw_sendmsg (STB_LOCAL)
ffffffff8193da5e-ffffffff8193daab: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff819ed8a0-ffffffff819ee04c: raw_sendmsg (STB_LOCAL)
ffffffff819ee76e-ffffffff819ee7bb: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int raw_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (0)
Location: net/ipv4/raw.c:498
Inline: False
```
**Symbols:**

```
ffffffff819f7790-ffffffff819f80ad: raw_sendmsg (STB_LOCAL)
ffffffff819f87d0-ffffffff819f881d: raw_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
