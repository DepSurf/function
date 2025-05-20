# Function: <code>neigh_add_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817259a0)
Location: net/core/neighbour.c:165
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_update
```
**Symbols:**

```
ffffffff817259a0-ffffffff817259dc: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8178f440)
Location: net/core/neighbour.c:165
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff8178f440-ffffffff8178f47c: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bccf0)
Location: net/core/neighbour.c:166
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff817bccf0-ffffffff817bcd2c: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817db440)
Location: net/core/neighbour.c:202
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff817db440-ffffffff817db47c: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81855c00)
Location: net/core/neighbour.c:202
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81855c00-ffffffff81855c42: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:205
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff818a10c0-ffffffff818a10eb: neigh_add_timer (STB_LOCAL)
ffffffff818a56f9-ffffffff818a5716: neigh_add_timer.cold.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff818c8c8c)
Location: net/core/neighbour.c:259
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff818c3a20-ffffffff818c3a4b: neigh_add_timer (STB_LOCAL)
ffffffff818c8c8c-ffffffff818c8ca9: neigh_add_timer.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff8191581c)
Location: net/core/neighbour.c:259
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff8190fc80-ffffffff8190fcab: neigh_add_timer (STB_LOCAL)
ffffffff8191581c-ffffffff81915839: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81947e8c)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff819422f0-ffffffff8194231b: neigh_add_timer (STB_LOCAL)
ffffffff81947e8c-ffffffff81947ea9: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81a18031)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81a13090-ffffffff81a130ec: neigh_add_timer (STB_LOCAL)
ffffffff81a18031-ffffffff81a1804e: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81c315b6)
Location: net/core/neighbour.c:258
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81a13400-ffffffff81a1345c: neigh_add_timer (STB_LOCAL)
ffffffff81c315b6-ffffffff81c315d3: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81c238e3)
Location: net/core/neighbour.c:262
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff819f9fc0-ffffffff819fa01c: neigh_add_timer (STB_LOCAL)
ffffffff81c238e3-ffffffff81c23900: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81d36a96)
Location: net/core/neighbour.c:262
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81aab960-ffffffff81aab9bc: neigh_add_timer (STB_LOCAL)
ffffffff81d36a96-ffffffff81d36ab3: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81f0336f)
Location: net/core/neighbour.c:290
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81c24690-ffffffff81c246f8: neigh_add_timer (STB_LOCAL)
ffffffff81f0336f-ffffffff81f0338c: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd6ea0)
Location: net/core/neighbour.c:290
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81dd6ea0-ffffffff81dd6f8a: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e47cd0)
Location: net/core/neighbour.c:290
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81e47cd0-ffffffff81e47dba: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f06980)
Location: net/core/neighbour.c:298
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81f06980-ffffffff81f06a6a: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be1cd0)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffff800010be1cd0-ffff800010be1d28: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfccdc)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
c0cfccdc-c0cfcd2c: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc42a0)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
c000000000cc42a0-c000000000cc4320: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe000768af6)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffe000768af6-ffffffe000768b54: neigh_add_timer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff818e7e5c)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff818e22c0-ffffffff818e22eb: neigh_add_timer (STB_LOCAL)
ffffffff818e7e5c-ffffffff818e7e79: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff818a1c9c)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff8189c100-ffffffff8189c12b: neigh_add_timer (STB_LOCAL)
ffffffff818a1c9c-ffffffff818a1cb9: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81938e8c)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff819332f0-ffffffff8193331b: neigh_add_timer (STB_LOCAL)
ffffffff81938e8c-ffffffff81938ea9: neigh_add_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void neigh_add_timer(struct neighbour *n, long unsigned int when);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff8195a69c)
Location: net/core/neighbour.c:256
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
**Symbols:**

```
ffffffff81954c20-ffffffff81954c4b: neigh_add_timer (STB_LOCAL)
ffffffff8195a69c-ffffffff8195a6b9: neigh_add_timer.cold (STB_LOCAL)
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
