# Function: <code>napi_hash_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void napi_hash_add(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716c90)
Location: net/core/dev.c:4685
Inline: True
```
**Symbols:**

```
ffffffff81716c90-ffffffff81716d5b: napi_hash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void napi_hash_add(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177eb80)
Location: net/core/dev.c:5022
Inline: True
Direct callers:
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff8177eb80-ffffffff8177ec46: napi_hash_add (STB_GLOBAL)
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
In net/core/dev.c (ffffffff817ab778)
Location: net/core/dev.c:5167
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff817c9dc8)
Location: net/core/dev.c:5371
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff818436e8)
Location: net/core/dev.c:5512
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff81891818)
Location: net/core/dev.c:5642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff818b239c)
Location: net/core/dev.c:6195
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff818fedac)
Location: net/core/dev.c:6205
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff8193111b)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void napi_hash_add(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a052f0)
Location: net/core/dev.c:6531
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff81a052f0-ffffffff81a053cb: napi_hash_add (STB_LOCAL)
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
In net/core/dev.c (ffffffff81a069f3)
Location: net/core/dev.c:6663
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819edcc6)
Location: net/core/dev.c:6784
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9ef24)
Location: net/core/dev.c:6770
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11d04)
Location: net/core/dev.c:6256
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc38fa)
Location: net/core/dev.c:6245
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e32d9a)
Location: net/core/dev.c:6225
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef1d13)
Location: net/core/dev.c:6307
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add_weight
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
In net/core/dev.c (ffff800010bce89c)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (c0ce55a4)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (c000000000ca5e80)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffe000758c18)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff818d111b)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff8188afcb)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff8192211b)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
In net/core/dev.c (ffffffff8194003b)
Location: net/core/dev.c:6141
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
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
</ul>
