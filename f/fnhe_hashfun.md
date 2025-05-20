# Function: <code>fnhe_hashfun</code>

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
In net/ipv4/route.c (ffffffff817546b5)
Location: net/ipv4/route.c:599
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff817c103a)
Location: net/ipv4/route.c:605
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff817f063a)
Location: net/ipv4/route.c:608
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81810a7e)
Location: net/ipv4/route.c:626
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff8188fefa)
Location: net/ipv4/route.c:629
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff818e2e46)
Location: net/ipv4/route.c:612
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff8190fce6)
Location: net/ipv4/route.c:612
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff819722e6)
Location: net/ipv4/route.c:620
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff819a8c56)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81a93516)
Location: net/ipv4/route.c:620
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81a9d3c6)
Location: net/ipv4/route.c:620
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 fnhe_hashfun(__be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a85930)
Location: net/ipv4/route.c:603
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81a85930-ffffffff81a859d1: fnhe_hashfun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 fnhe_hashfun(__be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b40140)
Location: net/ipv4/route.c:611
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81b40140-ffffffff81b401de: fnhe_hashfun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 fnhe_hashfun(__be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cccac0)
Location: net/ipv4/route.c:614
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81cccac0-ffffffff81cccb72: fnhe_hashfun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 fnhe_hashfun(__be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8c9b0)
Location: net/ipv4/route.c:614
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81e8c9b0-ffffffff81e8ca62: fnhe_hashfun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 fnhe_hashfun(__be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eeb0e0)
Location: net/ipv4/route.c:614
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81eeb0e0-ffffffff81eeb192: fnhe_hashfun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 fnhe_hashfun(__be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81faf100)
Location: net/ipv4/route.c:614
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81faf100-ffffffff81faf1b2: fnhe_hashfun (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5986c)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (c0d6815c)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (c000000000d5a164)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffe0007c24ce)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81948ac6)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff819025b6)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff819b3296)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff819bc966)
Location: net/ipv4/route.c:621
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
