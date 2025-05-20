# Function: <code>xdp_put_umem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff819ccf40)
Location: net/xdp/xdp_umem.c:190
Inline: False
```
**Symbols:**

```
ffffffff819ccf40-ffffffff819ccf96: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a06190)
Location: net/xdp/xdp_umem.c:241
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81a06190-ffffffff81a061e6: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a75aa0)
Location: net/xdp/xdp_umem.c:231
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81a75aa0-ffffffff81a75af4: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81aac920)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81aac920-ffffffff81aac974: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba8c10)
Location: net/xdp/xdp_umem.c:235
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81ba8c10-ffffffff81ba8c80: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81bb8400)
Location: net/xdp/xdp_umem.c:81
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81bb8400-ffffffff81bb850e: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba75c0)
Location: net/xdp/xdp_umem.c:81
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81ba75c0-ffffffff81ba76ce: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81c75240)
Location: net/xdp/xdp_umem.c:81
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81c75240-ffffffff81c7534e: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81e193c0)
Location: net/xdp/xdp_umem.c:81
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81e193c0-ffffffff81e194f6: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ff06a0)
Location: net/xdp/xdp_umem.c:79
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81ff06a0-ffffffff81ff07d6: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff8206c850)
Location: net/xdp/xdp_umem.c:79
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff8206c850-ffffffff8206c986: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem, bool defer_cleanup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff82140670)
Location: net/xdp/xdp_umem.c:79
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff82140670-ffffffff821407a6: xdp_put_umem (STB_GLOBAL)
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
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d811e8)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffff800010d811e8-ffff800010d8125c: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c0e7b720)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
c0e7b720-c0e7b788: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c000000000ec1080)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
c000000000ec1080-c000000000ec1124: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffe0008ad6d0)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffe0008ad6d0-ffffffe0008ad73c: xdp_put_umem (STB_GLOBAL)
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
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a4bcb0)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81a4bcb0-ffffffff81a4bd04: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a088a0)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81a088a0-ffffffff81a088f4: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ab7b60)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81ab7b60-ffffffff81ab7bb4: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_put_umem(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ac3f80)
Location: net/xdp/xdp_umem.c:271
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_destruct
```
**Symbols:**

```
ffffffff81ac3f80-ffffffff81ac3fd4: xdp_put_umem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool defer_cleanup</code>
</li>
</ul>
</details>
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
