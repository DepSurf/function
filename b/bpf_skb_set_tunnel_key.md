# Function: <code>bpf_skb_set_tunnel_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 r1, u64 r2, u64 size, u64 flags, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731b70)
Location: net/core/filter.c:1584
Inline: False
```
**Symbols:**

```
ffffffff81731b70-ffffffff81731c11: bpf_skb_set_tunnel_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 r1, u64 r2, u64 size, u64 flags, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179cd90)
Location: net/core/filter.c:2165
Inline: False
```
**Symbols:**

```
ffffffff8179cd90-ffffffff8179cfbf: bpf_skb_set_tunnel_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cada0)
Location: net/core/filter.c:2421
Inline: False
```
**Symbols:**

```
ffffffff817cada0-ffffffff817cafc9: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9e80)
Location: net/core/filter.c:2580
Inline: False
```
**Symbols:**

```
ffffffff817e9e80-ffffffff817ea106: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865510)
Location: net/core/filter.c:2978
Inline: False
```
**Symbols:**

```
ffffffff81865510-ffffffff81865796: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3600
Inline: False
```
**Symbols:**

```
ffffffff818b879c-ffffffff818b87a8: bpf_skb_set_tunnel_key.cold.94 (STB_LOCAL)
ffffffff818b3030-ffffffff818b32d4: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3788
Inline: False
```
**Symbols:**

```
ffffffff818df3f4-ffffffff818df400: bpf_skb_set_tunnel_key.cold.101 (STB_LOCAL)
ffffffff818d7e80-ffffffff818d8126: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3925
Inline: False
```
**Symbols:**

```
ffffffff8192d9be-ffffffff8192d9dd: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81925c00-ffffffff81925e90: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffffffff8195fcbe-ffffffff8195fcca: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81958250-ffffffff819584e7: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3904
Inline: False
```
**Symbols:**

```
ffffffff81a33209-ffffffff81a33215: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81a29b40-ffffffff81a29dd8: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4312
Inline: False
```
**Symbols:**

```
ffffffff81c31755-ffffffff81c31761: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81a2a4a0-ffffffff81a2a738: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4251
Inline: False
```
**Symbols:**

```
ffffffff81c23a5e-ffffffff81c23a6a: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81a11640-ffffffff81a118cf: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4309
Inline: False
```
**Symbols:**

```
ffffffff81d36f91-ffffffff81d36f9d: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81ac2b20-ffffffff81ac2dd2: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d7c0)
Location: net/core/filter.c:4595
Inline: False
```
**Symbols:**

```
ffffffff81c3d7c0-ffffffff81c3da71: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df3ca0)
Location: net/core/filter.c:4613
Inline: False
```
**Symbols:**

```
ffffffff81df3ca0-ffffffff81df3f51: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e65880)
Location: net/core/filter.c:4664
Inline: False
```
**Symbols:**

```
ffffffff81e65880-ffffffff81e65b6c: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f24a30)
Location: net/core/filter.c:4738
Inline: False
```
**Symbols:**

```
ffffffff81f24a30-ffffffff81f24d1c: bpf_skb_set_tunnel_key (STB_GLOBAL)
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c01078)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffff800010c01078-ffff800010c012dc: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d148f0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
c0d148f0-c0d14b6c: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce0bf0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
c000000000ce0bf0-c000000000ce0f08: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f19e)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffffffe00077f19e-ffffffe00077f3e0: bpf_skb_set_tunnel_key (STB_GLOBAL)
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffffffff818ffc8e-ffffffff818ffc9a: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff818f8220-ffffffff818f84b7: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffffffff818b9abe-ffffffff818b9aca: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff818b2050-ffffffff818b22e7: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffffffff81950cbe-ffffffff81950cca: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff81949250-ffffffff819494e7: bpf_skb_set_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3932
Inline: False
```
**Symbols:**

```
ffffffff8197268e-ffffffff8197269a: bpf_skb_set_tunnel_key.cold (STB_LOCAL)
ffffffff8196ab60-ffffffff8196adf7: bpf_skb_set_tunnel_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 from</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
