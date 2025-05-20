# Function: <code>crypto_ahash_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff813a3250)
Location: crypto/ahash.c:349
Inline: True
Direct callers:
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_digest
```
**Symbols:**

```
ffffffff813a3250-ffffffff813a32a5: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff813df450)
Location: crypto/ahash.c:332
Inline: True
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff813df450-ffffffff813df4b1: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff813f79e0)
Location: crypto/ahash.c:332
Inline: True
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff813f79e0-ffffffff813f7a41: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81403880)
Location: crypto/ahash.c:347
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff81403880-ffffffff814038ea: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8142bfe0)
Location: crypto/ahash.c:353
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff8142bfe0-ffffffff8142c049: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8145ecd0)
Location: crypto/ahash.c:353
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff8145ecd0-ffffffff8145ed39: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8147c640)
Location: crypto/ahash.c:364
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff8147c640-ffffffff8147c6a9: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814aafb0)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff814aafb0-ffffffff814ab018: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814c5c70)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff814c5c70-ffffffff814c5cd8: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81524560)
Location: crypto/ahash.c:361
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff81524560-ffffffff815245c7: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81541430)
Location: crypto/ahash.c:328
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff81541430-ffffffff81541497: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81549a60)
Location: crypto/ahash.c:328
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff81549a60-ffffffff81549ac7: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815aa240)
Location: crypto/ahash.c:328
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff815aa240-ffffffff815aa2a7: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81651690)
Location: crypto/ahash.c:328
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff81651690-ffffffff81651701: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8170b370)
Location: crypto/ahash.c:328
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff8170b370-ffffffff8170b3e1: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *), bool has_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81745000)
Location: crypto/ahash.c:286
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff81745000-ffffffff81745097: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffff8000105c0a80)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffff8000105c0a80-ffff8000105c0b18: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c076e550)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
c076e550-c076e5d0: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c000000000748db0)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
c000000000748db0-c000000000748e9c: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffe00040594a)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffe00040594a-ffffffe0004059c2: crypto_ahash_op (STB_LOCAL)
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
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814be250)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff814be250-ffffffff814be2b8: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814aec70)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff814aec70-ffffffff814aecd8: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814ba2e0)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff814ba2e0-ffffffff814ba348: crypto_ahash_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request *req, int (*op)(struct ahash_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814d2d90)
Location: crypto/ahash.c:359
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
```
**Symbols:**

```
ffffffff814d2d90-ffffffff814d2df8: crypto_ahash_op (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool has_state</code>
</li>
</ul>
</details>
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
