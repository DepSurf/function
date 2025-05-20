# Function: <code>has_bh_in_lru</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242580)
Location: fs/buffer.c:1456
Inline: False
```
**Symbols:**

```
ffffffff81242580-ffffffff812425bc: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126a8e0)
Location: fs/buffer.c:1446
Inline: False
```
**Symbols:**

```
ffffffff8126a8e0-ffffffff8126a91c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127d9f0)
Location: fs/buffer.c:1446
Inline: False
```
**Symbols:**

```
ffffffff8127d9f0-ffffffff8127da2c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128b610)
Location: fs/buffer.c:1441
Inline: False
```
**Symbols:**

```
ffffffff8128b610-ffffffff8128b64e: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ae190)
Location: fs/buffer.c:1401
Inline: False
```
**Symbols:**

```
ffffffff812ae190-ffffffff812ae1ce: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d5fb0)
Location: fs/buffer.c:1372
Inline: False
```
**Symbols:**

```
ffffffff812d5fb0-ffffffff812d5fec: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb380)
Location: fs/buffer.c:1380
Inline: False
```
**Symbols:**

```
ffffffff812eb380-ffffffff812eb3bc: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ca30)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffff8130ca30-ffffffff8130ca6c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131fa40)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffff8131fa40-ffffffff8131fa7c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81359180)
Location: fs/buffer.c:1425
Inline: False
```
**Symbols:**

```
ffffffff81359180-ffffffff813591bc: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81366f50)
Location: fs/buffer.c:1424
Inline: False
```
**Symbols:**

```
ffffffff81366f50-ffffffff81366f8c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136d940)
Location: fs/buffer.c:1434
Inline: False
Direct callers:
  - mm/swap.c:__lru_add_drain_all
```
**Symbols:**

```
ffffffff8136d940-ffffffff8136d97c: has_bh_in_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bc600)
Location: fs/buffer.c:1409
Inline: False
Direct callers:
  - mm/swap.c:__lru_add_drain_all
```
**Symbols:**

```
ffffffff813bc600-ffffffff813bc66b: has_bh_in_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814426e0)
Location: fs/buffer.c:1408
Inline: False
Direct callers:
  - mm/swap.c:__lru_add_drain_all
```
**Symbols:**

```
ffffffff814426e0-ffffffff8144275f: has_bh_in_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d16c0)
Location: fs/buffer.c:1397
Inline: False
Direct callers:
  - mm/swap.c:__lru_add_drain_all
```
**Symbols:**

```
ffffffff814d16c0-ffffffff814d173f: has_bh_in_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81507e40)
Location: fs/buffer.c:1509
Inline: False
Direct callers:
  - mm/swap.c:__lru_add_drain_all
```
**Symbols:**

```
ffffffff81507e40-ffffffff81507ec3: has_bh_in_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153cc80)
Location: fs/buffer.c:1504
Inline: False
Direct callers:
  - mm/swap.c:__lru_add_drain_all
```
**Symbols:**

```
ffffffff8153cc80-ffffffff8153cd03: has_bh_in_lru (STB_GLOBAL)
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
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d7500)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffff8000103d7500-ffff8000103d756c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b0fb0)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
c05b0fb0-c05b1004: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004db970)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
c0000000004db970-c0000000004db9d8: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000290e20)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffe000290e20-ffffffe000290e74: has_bh_in_lru (STB_LOCAL)
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
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318020)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81318020-ffffffff8131805c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81308c10)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81308c10-ffffffff81308c4c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81315af0)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81315af0-ffffffff81315b2c: has_bh_in_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_bh_in_lru(int cpu, void *dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81327660)
Location: fs/buffer.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81327660-ffffffff8132769c: has_bh_in_lru (STB_LOCAL)
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
