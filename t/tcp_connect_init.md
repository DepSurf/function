# Function: <code>tcp_connect_init</code>

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
In net/ipv4/tcp_output.c (ffffffff81777966)
Location: net/ipv4/tcp_output.c:3057
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff817e4986)
Location: net/ipv4/tcp_output.c:3109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81814dd6)
Location: net/ipv4/tcp_output.c:3233
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81834fe0)
Location: net/ipv4/tcp_output.c:3255
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff818b4469)
Location: net/ipv4/tcp_output.c:3309
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81909a7f)
Location: net/ipv4/tcp_output.c:3290
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81937d2f)
Location: net/ipv4/tcp_output.c:3322
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81999450)
Location: net/ipv4/tcp_output.c:3356
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81999450-ffffffff81999969: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819cfe30)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff819cfe30-ffffffff819d0357: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abce90)
Location: net/ipv4/tcp_output.c:3461
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81abce90-ffffffff81abd34d: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac85f0)
Location: net/ipv4/tcp_output.c:3641
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81ac85f0-ffffffff81ac8a93: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab3320)
Location: net/ipv4/tcp_output.c:3638
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81ab3320-ffffffff81ab389e: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3639
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81b70150-ffffffff81b7071d: tcp_connect_init (STB_LOCAL)
ffffffff81d3aefa-ffffffff81d3b082: tcp_connect_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3646
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81cff6f0-ffffffff81cffc9b: tcp_connect_init (STB_LOCAL)
ffffffff81f077d1-ffffffff81f07953: tcp_connect_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3648
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81ec4790-ffffffff81ec4d3b: tcp_connect_init (STB_LOCAL)
ffffffff820af263-ffffffff820af3e5: tcp_connect_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3730
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81f23100-ffffffff81f2369b: tcp_connect_init (STB_LOCAL)
ffffffff8213064e-ffffffff821307b4: tcp_connect_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3832
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81fe7590-ffffffff81fe7a6e: tcp_connect_init (STB_LOCAL)
ffffffff8221207c-ffffffff822120e0: tcp_connect_init.cold (STB_LOCAL)
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
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c82510)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffff800010c82510-ffff800010c82914: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d91b78)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
c0d91b78-c0d91fdc: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8e050)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
c000000000d8e050-c000000000d8e5bc: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e4862)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffe0007e4862-ffffffe0007e4c26: tcp_connect_init (STB_LOCAL)
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
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196fca0)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff8196fca0-ffffffff819701c7: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81929770)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81929770-ffffffff81929c97: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819da470)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff819da470-ffffffff819da997: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_connect_init(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e40f0)
Location: net/ipv4/tcp_output.c:3388
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff819e40f0-ffffffff819e4626: tcp_connect_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
