# Function: <code>napi_hash_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713910)
Location: net/core/dev.c:4712
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_free_queues
```
**Symbols:**

```
ffffffff81713910-ffffffff8171396f: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177b580)
Location: net/core/dev.c:5047
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_free_queues
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff8177b580-ffffffff8177b5e2: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a8bf0)
Location: net/core/dev.c:5191
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff817a8bf0-ffffffff817a8c52: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7290)
Location: net/core/dev.c:5395
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff817c7290-ffffffff817c72f2: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81840e70)
Location: net/core/dev.c:5536
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff81840e70-ffffffff81840ed2: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890e90)
Location: net/core/dev.c:5666
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff81890e90-ffffffff81890ef3: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b1470)
Location: net/core/dev.c:6219
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff818b1470-ffffffff818b14d3: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fe220)
Location: net/core/dev.c:6229
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff818fe220-ffffffff818fe285: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81930550)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff81930550-ffffffff819305b5: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04140)
Location: net/core/dev.c:6555
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff81a04140-ffffffff81a041a8: napi_hash_del (STB_GLOBAL)
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
In net/core/dev.c (ffffffff81a061ca)
Location: net/core/dev.c:6686
Inline: True
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
In net/core/dev.c (ffffffff819eccfa)
Location: net/core/dev.c:6807
Inline: True
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
In net/core/dev.c (ffffffff81a9de85)
Location: net/core/dev.c:6793
Inline: True
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
In net/core/dev.c (ffffffff81c0f003)
Location: net/core/dev.c:6279
Inline: True
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
In net/core/dev.c (ffffffff81dbed43)
Location: net/core/dev.c:6268
Inline: True
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
In net/core/dev.c (ffffffff81e2e913)
Location: net/core/dev.c:6248
Inline: True
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
In net/core/dev.c (ffffffff81eed293)
Location: net/core/dev.c:6330
Inline: True
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
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcc408)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffff800010bcc408-ffff800010bcc518: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce459c)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
c0ce459c-c0ce4614: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cab630)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
c000000000cab630-c000000000cab750: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000757f18)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffe000757f18-ffffffe000757fb4: napi_hash_del (STB_GLOBAL)
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
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d0550)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff818d0550-ffffffff818d05b5: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188a430)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff8188a430-ffffffff8188a495: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81921550)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff81921550-ffffffff819215b5: napi_hash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool napi_hash_del(struct napi_struct *napi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193be30)
Location: net/core/dev.c:6165
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_del
```
**Symbols:**

```
ffffffff8193be30-ffffffff8193be97: napi_hash_del (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
