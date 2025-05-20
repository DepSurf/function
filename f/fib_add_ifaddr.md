# Function: <code>fib_add_ifaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179b6d0)
Location: net/ipv4/fib_frontend.c:842
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8179b6d0-ffffffff8179b84f: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818092c0)
Location: net/ipv4/fib_frontend.c:842
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff818092c0-ffffffff81809443: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8183a3d0)
Location: net/ipv4/fib_frontend.c:842
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8183a3d0-ffffffff8183a553: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185b950)
Location: net/ipv4/fib_frontend.c:860
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8185b950-ffffffff8185bacb: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818db840)
Location: net/ipv4/fib_frontend.c:884
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff818db840-ffffffff818db9bb: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:891
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81932c24-ffffffff81932c3c: fib_add_ifaddr.cold.30 (STB_LOCAL)
ffffffff819323a0-ffffffff81932518: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1001
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff819624b4-ffffffff819624cc: fib_add_ifaddr.cold.31 (STB_LOCAL)
ffffffff81961c00-ffffffff81961d78: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1096
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff819c71f2-ffffffff819c720a: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff819c6950-ffffffff819c6ad6: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff819fdda2-ffffffff819fddba: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff819fd500-ffffffff819fd686: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1090
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81aec7d1-ffffffff81aec7e9: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81aebf10-ffffffff81aec073: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1090
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81c32987-ffffffff81c3299f: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81af8e10-ffffffff81af8f73: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1092
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81c24c5b-ffffffff81c24c73: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81ae45d0-ffffffff81ae4733: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1092
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81d3c808-ffffffff81d3c820: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81ba3f20-ffffffff81ba4063: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1103
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81f09067-ffffffff81f0907f: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81d36800-ffffffff81d36977: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efee70)
Location: net/ipv4/fib_frontend.c:1106
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81efee70-ffffffff81efeffc: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5e900)
Location: net/ipv4/fib_frontend.c:1109
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81f5e900-ffffffff81f5ea8c: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff82024ed0)
Location: net/ipv4/fib_frontend.c:1109
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff82024ed0-ffffffff8202505c: fib_add_ifaddr (STB_GLOBAL)
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
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb56e0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffff800010cb56e0-ffff800010cb586c: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc1054)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
c0dc1054-c0dc11e0: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcd1c0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
c000000000dcd1c0-c000000000dcd408: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080cfd2)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffe00080cfd2-ffffffe00080d12a: fib_add_ifaddr (STB_GLOBAL)
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
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff8199db42-ffffffff8199db5a: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff8199d2a0-ffffffff8199d426: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81957602-ffffffff8195761a: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81956d60-ffffffff81956ee6: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81a083e2-ffffffff81a083fa: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81a07b40-ffffffff81a07cc6: fib_add_ifaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fib_add_ifaddr(struct in_ifaddr *ifa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:1099
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
**Symbols:**

```
ffffffff81a12b32-ffffffff81a12b4a: fib_add_ifaddr.cold (STB_LOCAL)
ffffffff81a12280-ffffffff81a12406: fib_add_ifaddr (STB_GLOBAL)
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
