# Function: <code>__inet_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762e00)
Location: net/ipv4/inet_hashtables.c:452
Inline: False
```
**Symbols:**

```
ffffffff81762e00-ffffffff81762ec2: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk, int (*saddr_same)(const struct sock *, const struct sock *, bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf0d0)
Location: net/ipv4/inet_hashtables.c:462
Inline: False
```
**Symbols:**

```
ffffffff817cf0d0-ffffffff817cf325: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk, int (*saddr_same)(const struct sock *, const struct sock *, bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817feee0)
Location: net/ipv4/inet_hashtables.c:464
Inline: False
```
**Symbols:**

```
ffffffff817feee0-ffffffff817ff11c: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181f180)
Location: net/ipv4/inet_hashtables.c:458
Inline: False
```
**Symbols:**

```
ffffffff8181f180-ffffffff8181f38d: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189e0f0)
Location: net/ipv4/inet_hashtables.c:462
Inline: False
```
**Symbols:**

```
ffffffff8189e0f0-ffffffff8189e2ed: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2ab0)
Location: net/ipv4/inet_hashtables.c:576
Inline: False
```
**Symbols:**

```
ffffffff818f2ab0-ffffffff818f2d70: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81920520)
Location: net/ipv4/inet_hashtables.c:541
Inline: False
```
**Symbols:**

```
ffffffff81920520-ffffffff819207fe: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: net/ipv4/inet_hashtables.c:537
Inline: False
```
**Symbols:**

```
ffffffff81983667-ffffffff8198367a: __inet_hash.cold (STB_LOCAL)
ffffffff81982e50-ffffffff81983138: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b96b0)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffffffff819b96b0-ffffffff819b99a2: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa4200)
Location: net/ipv4/inet_hashtables.c:539
Inline: False
```
**Symbols:**

```
ffffffff81aa4200-ffffffff81aa4410: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aae840)
Location: net/ipv4/inet_hashtables.c:631
Inline: False
```
**Symbols:**

```
ffffffff81aae840-ffffffff81aaea52: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a999c0)
Location: net/ipv4/inet_hashtables.c:631
Inline: False
```
**Symbols:**

```
ffffffff81a999c0-ffffffff81a99ca0: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54e30)
Location: net/ipv4/inet_hashtables.c:633
Inline: False
```
**Symbols:**

```
ffffffff81b54e30-ffffffff81b55108: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2a90)
Location: net/ipv4/inet_hashtables.c:591
Inline: False
```
**Symbols:**

```
ffffffff81ce2a90-ffffffff81ce2cc5: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea3f70)
Location: net/ipv4/inet_hashtables.c:720
Inline: False
```
**Symbols:**

```
ffffffff81ea3f70-ffffffff81ea41be: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f027c0)
Location: net/ipv4/inet_hashtables.c:707
Inline: False
```
**Symbols:**

```
ffffffff81f027c0-ffffffff81f02a39: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc6b80)
Location: net/ipv4/inet_hashtables.c:728
Inline: False
```
**Symbols:**

```
ffffffff81fc6b80-ffffffff81fc6df8: __inet_hash (STB_GLOBAL)
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
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6adf0)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffff800010c6adf0-ffff800010c6b130: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d79edc)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
c0d79edc-c0d7a210: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d701a0)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
c000000000d701a0-c000000000d70610: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0b02)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffffffe0007d0b02-ffffffe0007d0dfc: __inet_hash (STB_GLOBAL)
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
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959520)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffffffff81959520-ffffffff81959812: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81913010)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffffffff81913010-ffffffff81913302: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3cf0)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffffffff819c3cf0-ffffffff819c3fe2: __inet_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __inet_hash(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cd740)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
```
**Symbols:**

```
ffffffff819cd740-ffffffff819cda52: __inet_hash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*saddr_same)(const struct sock *, const struct sock *, bool)</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int (*saddr_same)(const struct sock *, const struct sock *, bool)</code>
</li>
</ul>
</details>
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
