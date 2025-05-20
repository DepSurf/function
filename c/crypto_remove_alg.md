# Function: <code>crypto_remove_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_remove_alg(struct crypto_alg *alg, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139dcd0)
Location: crypto/algapi.c:376
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_template
```
**Symbols:**

```
ffffffff8139dcd0-ffffffff8139dd2e: crypto_remove_alg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_remove_alg(struct crypto_alg *alg, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813dac10)
Location: crypto/algapi.c:375
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_template
```
**Symbols:**

```
ffffffff813dac10-ffffffff813dac71: crypto_remove_alg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_remove_alg(struct crypto_alg *alg, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f2550)
Location: crypto/algapi.c:376
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_template
```
**Symbols:**

```
ffffffff813f2550-ffffffff813f25b1: crypto_remove_alg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_remove_alg(struct crypto_alg *alg, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fe840)
Location: crypto/algapi.c:376
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_template
```
**Symbols:**

```
ffffffff813fe840-ffffffff813fe8a1: crypto_remove_alg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_remove_alg(struct crypto_alg *alg, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81426e00)
Location: crypto/algapi.c:388
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_template
```
**Symbols:**

```
ffffffff81426e00-ffffffff81426e61: crypto_remove_alg (STB_LOCAL)
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
In crypto/algapi.c (ffffffff8145a69c)
Location: crypto/algapi.c:397
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff81477bfc)
Location: crypto/algapi.c:406
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff814a58a8)
Location: crypto/algapi.c:387
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff814c0558)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff815206a8)
Location: crypto/algapi.c:434
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff8153d538)
Location: crypto/algapi.c:434
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff81545c18)
Location: crypto/algapi.c:434
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff815a6128)
Location: crypto/algapi.c:434
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff8164d483)
Location: crypto/algapi.c:450
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff817064f3)
Location: crypto/algapi.c:471
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff817406e3)
Location: crypto/algapi.c:481
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffff81781583)
Location: crypto/algapi.c:482
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffff8000105b9c10)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (c0768568)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (c0000000007401d8)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
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
In crypto/algapi.c (ffffffe0003fffc4)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff814b8b38)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff814a9558)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff814b4bc8)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
In crypto/algapi.c (ffffffff814cd648)
Location: crypto/algapi.c:405
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
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
