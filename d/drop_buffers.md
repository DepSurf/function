# Function: <code>drop_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242c70)
Location: fs/buffer.c:3186
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff81242c70-ffffffff81242d12: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c7f0)
Location: fs/buffer.c:3245
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8126c7f0-ffffffff8126c8c8: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f850)
Location: fs/buffer.c:3286
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8127f850-ffffffff8127f928: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d070)
Location: fs/buffer.c:3273
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8128d070-ffffffff8128d125: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af860)
Location: fs/buffer.c:3241
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff812af860-ffffffff812af94a: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d76e0)
Location: fs/buffer.c:3212
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff812d76e0-ffffffff812d77c4: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ecb40)
Location: fs/buffer.c:3224
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff812ecb40-ffffffff812ecc24: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130e2f0)
Location: fs/buffer.c:3231
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8130e2f0-ffffffff8130e3d5: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321310)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff81321310-ffffffff813213fa: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135ba40)
Location: fs/buffer.c:3218
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8135ba40-ffffffff8135bb31: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369ff0)
Location: fs/buffer.c:3199
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff81369ff0-ffffffff8136a0de: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81370c00)
Location: fs/buffer.c:3220
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff81370c00-ffffffff81370cf6: drop_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff813bf850)
Location: fs/buffer.c:3199
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff813bf850-ffffffff813bf943: drop_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff814437d0)
Location: fs/buffer.c:3184
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff814437d0-ffffffff814438aa: drop_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff814d2020)
Location: fs/buffer.c:2789
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff814d2020-ffffffff814d20fa: drop_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81509a30)
Location: fs/buffer.c:2927
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff81509a30-ffffffff81509b0a: drop_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8153e860)
Location: fs/buffer.c:2887
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8153e860-ffffffff8153e93a: drop_buffers.constprop.0 (STB_LOCAL)
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
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8660)
Location: fs/buffer.c:3208
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffff8000103d8660-ffff8000103d8778: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b30c8)
Location: fs/buffer.c:3208
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
c05b30c8-c05b31ac: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004de880)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
c0000000004de880-c0000000004dea48: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292324)
Location: fs/buffer.c:3208
Inline: True
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffe000292324-ffffffe0002923e0: drop_buffers (STB_LOCAL)
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
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813198f0)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff813198f0-ffffffff813199da: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a4b0)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff8130a4b0-ffffffff8130a59a: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813173c0)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff813173c0-ffffffff813174aa: drop_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int drop_buffers(struct page *page, struct buffer_head **buffers_to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328fb0)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
```
**Symbols:**

```
ffffffff81328fb0-ffffffff8132909a: drop_buffers (STB_LOCAL)
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
