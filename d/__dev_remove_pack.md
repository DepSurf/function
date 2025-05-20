# Function: <code>__dev_remove_pack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713f90)
Location: net/core/dev.c:418
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81713f90-ffffffff8171405c: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177bd40)
Location: net/core/dev.c:422
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8177bd40-ffffffff8177be09: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a94e0)
Location: net/core/dev.c:421
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff817a94e0-ffffffff817a95a9: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7a80)
Location: net/core/dev.c:428
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff817c7a80-ffffffff817c7b49: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81841660)
Location: net/core/dev.c:431
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff81841660-ffffffff81841729: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:431
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff8189900d-ffffffff81899021: __dev_remove_pack.cold.158 (STB_LOCAL)
ffffffff818914a0-ffffffff81891563: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:433
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff818bb4bc-ffffffff818bb4d0: __dev_remove_pack.cold.167 (STB_LOCAL)
ffffffff818b2090-ffffffff818b2153: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:429
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff81907363-ffffffff81907377: __dev_remove_pack.cold (STB_LOCAL)
ffffffff818fe860-ffffffff818fe922: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff819399b0-ffffffff819399c4: __dev_remove_pack.cold (STB_LOCAL)
ffffffff81930ba0-ffffffff81930c62: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:553
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81a0ef12-ffffffff81a0ef26: __dev_remove_pack.cold (STB_LOCAL)
ffffffff81a047d0-ffffffff81a04892: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:556
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81c311ee-ffffffff81c31202: __dev_remove_pack.cold (STB_LOCAL)
ffffffff81a04ec0-ffffffff81a04f82: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:558
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81c234b9-ffffffff81c234cd: __dev_remove_pack.cold (STB_LOCAL)
ffffffff819eca10-ffffffff819ecad0: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:560
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81d361e4-ffffffff81d361f8: __dev_remove_pack.cold (STB_LOCAL)
ffffffff81a9da50-ffffffff81a9db10: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:581
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81f0265b-ffffffff81f0266f: __dev_remove_pack.cold (STB_LOCAL)
ffffffff81c0f8d0-ffffffff81c0f99b: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbf4f0)
Location: net/core/dev.c:581
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81dbf4f0-ffffffff81dbf5c9: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2f1a0)
Location: net/core/dev.c:579
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81e2f1a0-ffffffff81e2f279: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eede10)
Location: net/core/dev.c:596
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:fanout_add
```
**Symbols:**

```
ffffffff81eede10-ffffffff81eedee9: __dev_remove_pack (STB_GLOBAL)
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
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcd478)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffff800010bcd478-ffff800010bcd5ac: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce25d8)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
c0ce25d8-c0ce26bc: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca2100)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
c000000000ca2100-c000000000ca2298: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007585f6)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffe0007585f6-ffffffe000758718: __dev_remove_pack (STB_GLOBAL)
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
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff818d9980-ffffffff818d9994: __dev_remove_pack.cold (STB_LOCAL)
ffffffff818d0ba0-ffffffff818d0c62: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff818937c0-ffffffff818937d4: __dev_remove_pack.cold (STB_LOCAL)
ffffffff8188aa80-ffffffff8188ab42: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff8192a9b0-ffffffff8192a9c4: __dev_remove_pack.cold (STB_LOCAL)
ffffffff81921ba0-ffffffff81921c62: __dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:347
Inline: False
Direct callers:
  - net/core/dev.c:dev_remove_pack
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff8194b9f1-ffffffff8194ba05: __dev_remove_pack.cold (STB_LOCAL)
ffffffff8193ca70-ffffffff8193cb30: __dev_remove_pack (STB_GLOBAL)
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
