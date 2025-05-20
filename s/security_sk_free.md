# Function: <code>security_sk_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133f670)
Location: security/security.c:1299
Inline: False
Direct callers:
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_destruct
```
**Symbols:**

```
ffffffff8133f670-ffffffff8133f6a6: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374c90)
Location: security/security.c:1329
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81374c90-ffffffff81374cc6: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138b5c0)
Location: security/security.c:1350
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff8138b5c0-ffffffff8138b5f6: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a1200)
Location: security/security.c:2297
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff813a1200-ffffffff813a124f: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6c40)
Location: security/security.c:2158
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff813c6c40-ffffffff813c6c95: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f65a0)
Location: security/security.c:1460
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff813f65a0-ffffffff813f65d4: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411fa0)
Location: security/security.c:2218
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81411fa0-ffffffff81411fed: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f8d0)
Location: security/security.c:2237
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff8143f8d0-ffffffff8143f91f: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814591f0)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff814591f0-ffffffff8145923d: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac2dc)
Location: security/security.c:2599
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff814ac330-ffffffff814ac37d: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c98dc)
Location: security/security.c:2616
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff814c9930-ffffffff814c997d: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cff0c)
Location: security/security.c:2679
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff814cff60-ffffffff814cffad: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528c3c)
Location: security/security.c:2687
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81528c90-ffffffff81528cdd: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bdf75)
Location: security/security.c:2721
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff815be000-ffffffff815be055: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166a0a5)
Location: security/security.c:2701
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff8166a140-ffffffff8166a195: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a2685)
Location: security/security.c:4702
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff816a2720-ffffffff816a2775: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816df205)
Location: security/security.c:4886
Inline: True
Inline callers:
  - security/security.c:security_sk_alloc
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff816df2a0-ffffffff816df2f5: security_sk_free (STB_GLOBAL)
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
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010545258)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffff800010545258-ffff8000105452ac: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb128)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
c06fb128-c06fb180: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069b2f0)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
c00000000069b2f0-c00000000069b37c: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a1098)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffe0003a1098-ffffffe0003a10e0: security_sk_free (STB_GLOBAL)
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
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814517d0)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff814517d0-ffffffff8145181d: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442220)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81442220-ffffffff8144226d: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d870)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff8144d870-ffffffff8144d8bd: security_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_sk_free(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464c40)
Location: security/security.c:2276
Inline: False
Direct callers:
  - security/security.c:security_sk_alloc
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81464c40-ffffffff81464c8d: security_sk_free (STB_GLOBAL)
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
