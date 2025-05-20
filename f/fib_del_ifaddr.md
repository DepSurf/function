# Function: <code>fib_del_ifaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179b970)
Location: net/ipv4/fib_frontend.c:889
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8179b970-ffffffff8179bdd2: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81809570)
Location: net/ipv4/fib_frontend.c:889
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81809570-ffffffff818099df: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8183a680)
Location: net/ipv4/fib_frontend.c:889
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8183a680-ffffffff8183aaef: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185bbf0)
Location: net/ipv4/fib_frontend.c:907
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8185bbf0-ffffffff8185c069: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818dbae0)
Location: net/ipv4/fib_frontend.c:931
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff818dbae0-ffffffff818dbf59: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:964
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81932c3c-ffffffff81932c54: fib_del_ifaddr.cold.31 (STB_LOCAL)
ffffffff81932700-ffffffff81932b71: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1074
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff819624cc-ffffffff819624e4: fib_del_ifaddr.cold.32 (STB_LOCAL)
ffffffff81961f90-ffffffff81962401: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1169
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff819c720a-ffffffff819c723a: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff819c6ce0-ffffffff819c7141: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff819fddba-ffffffff819fddea: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff819fd890-ffffffff819fdcf1: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1163
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81aec7e9-ffffffff81aec819: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81aec2b0-ffffffff81aec70a: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1163
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81c3299f-ffffffff81c329cf: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81af91b0-ffffffff81af9623: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1165
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81c24c73-ffffffff81c24ca3: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81ae4970-ffffffff81ae4de3: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1163
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81d3c820-ffffffff81d3c850: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81ba42a0-ffffffff81ba4713: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1177
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81f0907f-ffffffff81f090af: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81d36bf0-ffffffff81d3707c: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81eff2a0)
Location: net/ipv4/fib_frontend.c:1180
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81eff2a0-ffffffff81eff752: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5ed30)
Location: net/ipv4/fib_frontend.c:1183
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81f5ed30-ffffffff81f5f1d7: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff82025300)
Location: net/ipv4/fib_frontend.c:1183
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff82025300-ffffffff820257a7: fib_del_ifaddr (STB_GLOBAL)
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
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb5ad8)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffff800010cb5ad8-ffff800010cb5ee4: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc1454)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
c0dc1454-c0dc18c0: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcd7a0)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
c000000000dcd7a0-c000000000dcdd74: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080d30a)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffe00080d30a-ffffffe00080d660: fib_del_ifaddr (STB_GLOBAL)
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
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8199db5a-ffffffff8199db8a: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff8199d630-ffffffff8199da91: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8195761a-ffffffff8195764a: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff819570f0-ffffffff81957551: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81a083fa-ffffffff81a0842a: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81a07ed0-ffffffff81a08331: fib_del_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fib_del_ifaddr(struct in_ifaddr *ifa, struct in_ifaddr *iprim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1172
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81a12b4a-ffffffff81a12b7a: fib_del_ifaddr.cold (STB_LOCAL)
ffffffff81a12610-ffffffff81a12a8a: fib_del_ifaddr (STB_GLOBAL)
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
