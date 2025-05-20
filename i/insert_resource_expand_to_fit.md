# Function: <code>insert_resource_expand_to_fit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810876c0)
Location: kernel/resource.c:850
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_reserve_resources_late
```
**Symbols:**

```
ffffffff810876c0-ffffffff81087736: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108a5b0)
Location: kernel/resource.c:888
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_reserve_resources_late
```
**Symbols:**

```
ffffffff8108a5b0-ffffffff8108a62d: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108f500)
Location: kernel/resource.c:888
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_reserve_resources_late
```
**Symbols:**

```
ffffffff8108f500-ffffffff8108f57d: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108c4b0)
Location: kernel/resource.c:888
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff8108c4b0-ffffffff8108c52e: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810931f0)
Location: kernel/resource.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810931f0-ffffffff8109326e: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff81096fe8-ffffffff8109700e: insert_resource_expand_to_fit.cold.16 (STB_LOCAL)
ffffffff81096c30-ffffffff81096c93: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:869
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff8109f318-ffffffff8109f33e: insert_resource_expand_to_fit.cold.16 (STB_LOCAL)
ffffffff8109ef50-ffffffff8109efb3: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810a39bd-ffffffff810a39ef: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810a3580-ffffffff810a35d7: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810a9fb1-ffffffff810a9fe3: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810a9bb0-ffffffff810a9c07: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810b1b5c-ffffffff810b1b8e: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810b1750-ffffffff810b17a7: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:890
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff81bdb845-ffffffff81bdb877: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810aceb0-ffffffff810acf07: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:882
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff81bcd937-ffffffff81bcd969: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810ae090-ffffffff810ae0e7: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:882
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff81ca431f-ffffffff81ca4351: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810bfc10-ffffffff810bfc67: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:869
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff81e53bb0-ffffffff81e53be2: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810d70d0-ffffffff810d713a: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f56b0)
Location: kernel/resource.c:870
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810f56b0-ffffffff810f5743: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101af0)
Location: kernel/resource.c:870
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff81101af0-ffffffff81101b83: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b240)
Location: kernel/resource.c:925
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff8110b240-ffffffff8110b2d3: insert_resource_expand_to_fit (STB_GLOBAL)
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
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101b80)
Location: kernel/resource.c:883
Inline: False
```
**Symbols:**

```
ffff800010101b80-ffff800010101c84: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035dfa4)
Location: kernel/resource.c:883
Inline: False
```
**Symbols:**

```
c035dfa4-c035e04c: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000149360)
Location: kernel/resource.c:883
Inline: False
```
**Symbols:**

```
c000000000149360-c00000000014943c: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8c38)
Location: kernel/resource.c:883
Inline: False
```
**Symbols:**

```
ffffffe0000c8c38-ffffffe0000c8cce: insert_resource_expand_to_fit (STB_GLOBAL)
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
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810a38d1-ffffffff810a3903: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810a34d0-ffffffff810a3527: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810922b1-ffffffff810922e3: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff81091eb0-ffffffff81091f07: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810a3881-ffffffff810a38b3: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810a3480-ffffffff810a34d7: insert_resource_expand_to_fit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void insert_resource_expand_to_fit(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources_late
```
**Symbols:**

```
ffffffff810ab93f-ffffffff810ab971: insert_resource_expand_to_fit.cold (STB_LOCAL)
ffffffff810ab530-ffffffff810ab582: insert_resource_expand_to_fit (STB_GLOBAL)
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
