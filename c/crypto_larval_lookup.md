# Function: <code>crypto_larval_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct crypto_alg *crypto_larval_lookup(const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c870)
Location: crypto/api.c:207
Inline: False
Direct callers:
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/ablkcipher.c:crypto_givcipher_default
```
**Symbols:**

```
ffffffff8139c870-ffffffff8139c9d8: crypto_larval_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct crypto_alg *crypto_larval_lookup(const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d9750)
Location: crypto/api.c:207
Inline: False
Direct callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
**Symbols:**

```
ffffffff813d9750-ffffffff813d98a1: crypto_larval_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct crypto_alg *crypto_larval_lookup(const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f1080)
Location: crypto/api.c:207
Inline: False
Direct callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
**Symbols:**

```
ffffffff813f1080-ffffffff813f11d2: crypto_larval_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_larval_lookup(const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff813fd494)
Location: crypto/api.c:207
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
Direct callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
**Symbols:**

```
ffffffff813fd310-ffffffff813fd44d: crypto_larval_lookup.part.10 (STB_LOCAL)
ffffffff813fd450-ffffffff813fd46d: crypto_larval_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_larval_lookup(const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff81425a14)
Location: crypto/api.c:208
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
Direct callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
**Symbols:**

```
ffffffff81425890-ffffffff814259cd: crypto_larval_lookup.part.10 (STB_LOCAL)
ffffffff814259d0-ffffffff814259ed: crypto_larval_lookup (STB_GLOBAL)
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
In crypto/api.c (ffffffff814586fa)
Location: crypto/api.c:220
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff81475b3a)
Location: crypto/api.c:220
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff814a3a2a)
Location: crypto/api.c:215
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff814be65a)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff8151ec8a)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff8153bada)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff815441ca)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff815a496a)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff8164b7a6)
Location: crypto/api.c:272
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff81704846)
Location: crypto/api.c:271
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff8173eb66)
Location: crypto/api.c:271
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff8177f9e6)
Location: crypto/api.c:271
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffff8000105b7638)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (c0766338)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (c00000000073c28c)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffe0003fde3c)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff814b6c3a)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff814a765a)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff814b2cca)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
In crypto/api.c (ffffffff814cb74a)
Location: crypto/api.c:217
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
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
</ul>
