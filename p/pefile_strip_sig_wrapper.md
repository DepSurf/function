# Function: <code>pefile_strip_sig_wrapper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813afb70)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813f320e)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8140ca7e)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8141ab5b)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814452bc)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81478253)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8149647a)
Location: crypto/asymmetric_keys/verify_pefile.c:126
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c436a)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dd24a)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153c790)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff8153c790-ffffffff8153c99c: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815592f0)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff815592f0-ffffffff815594fc: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81561c00)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81561c00-ffffffff81561e22: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c3030)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff815c3030-ffffffff815c3240: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166d600)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff8166d600-ffffffff8166d7e4: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817286c0)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff817286c0-ffffffff817288a3: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764a40)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81764a40-ffffffff81764bd8: pefile_strip_sig_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pefile_strip_sig_wrapper(const void *pebuf, struct pefile_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6660)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff817a6660-ffffffff817a67f8: pefile_strip_sig_wrapper (STB_LOCAL)
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
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d97c8)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (c0786b18)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (c0000000007698b0)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041ce3e)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d582a)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c624a)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d18ba)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea36a)
Location: crypto/asymmetric_keys/verify_pefile.c:122
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
