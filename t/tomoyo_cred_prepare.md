# Function: <code>tomoyo_cred_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81373030)
Location: security/tomoyo/tomoyo.c:33
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff81373030-ffffffff8137304e: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff813a9475)
Location: security/tomoyo/tomoyo.c:33
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff813a9450-ffffffff813a946e: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff813bffe5)
Location: security/tomoyo/tomoyo.c:33
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff813bffc0-ffffffff813bffde: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff813d6905)
Location: security/tomoyo/tomoyo.c:35
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff813d68d0-ffffffff813d68fd: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff813fce35)
Location: security/tomoyo/tomoyo.c:36
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff813fce00-ffffffff813fce30: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8142dd55)
Location: security/tomoyo/tomoyo.c:34
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff8142dd20-ffffffff8142dd41: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8144a6a5)
Location: security/tomoyo/tomoyo.c:36
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
```
**Symbols:**

```
ffffffff8144a670-ffffffff8144a6a0: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff814782d0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff814782d0-ffffffff8147831a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81491ff0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff81491ff0-ffffffff8149203a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff814e93f0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff814e93f0-ffffffff814e943a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81506710)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff81506710-ffffffff8150675a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8150d250)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8150d250-ffffffff8150d29a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8156ad90)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8156ad90-ffffffff8156adda: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81606e20)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff81606e20-ffffffff81606e70: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff816b8380)
Location: security/tomoyo/tomoyo.c:37
Inline: False
```
**Symbols:**

```
ffffffff816b8380-ffffffff816b83d0: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff816f0d50)
Location: security/tomoyo/tomoyo.c:37
Inline: False
```
**Symbols:**

```
ffffffff816f0d50-ffffffff816f0da0: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8172db20)
Location: security/tomoyo/tomoyo.c:37
Inline: False
```
**Symbols:**

```
ffffffff8172db20-ffffffff8172db70: tomoyo_cred_prepare (STB_LOCAL)
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
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffff8000105872e0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffff8000105872e0-ffff800010587364: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (c0738184)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
c0738184-c0738208: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (c0000000006f6910)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
c0000000006f6910-c0000000006f697c: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffe0003d6120)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffe0003d6120-ffffffe0003d616e: tomoyo_cred_prepare (STB_LOCAL)
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
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8148a5d0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8148a5d0-ffffffff8148a61a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8147aff0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8147aff0-ffffffff8147b03a: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81486670)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff81486670-ffffffff814866ba: tomoyo_cred_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_cred_prepare(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8149e1b0)
Location: security/tomoyo/tomoyo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8149e1b0-ffffffff8149e1fa: tomoyo_cred_prepare (STB_LOCAL)
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
