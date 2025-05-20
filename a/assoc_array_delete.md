# Function: <code>assoc_array_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81405f80)
Location: lib/assoc_array.c:1109
Inline: False
```
**Symbols:**

```
ffffffff81405f80-ffffffff814062a8: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8144db70)
Location: lib/assoc_array.c:1111
Inline: False
```
**Symbols:**

```
ffffffff8144db70-ffffffff8144de99: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8146c530)
Location: lib/assoc_array.c:1111
Inline: False
```
**Symbols:**

```
ffffffff8146c530-ffffffff8146c859: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81471c20)
Location: lib/assoc_array.c:1111
Inline: False
Direct callers:
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff81471c20-ffffffff81471f4c: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8149e360)
Location: lib/assoc_array.c:1094
Inline: False
Direct callers:
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff8149e360-ffffffff8149e691: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff814d35f0)
Location: lib/assoc_array.c:1081
Inline: False
Direct callers:
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff814d35f0-ffffffff814d38ef: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff814e7f50)
Location: lib/assoc_array.c:1083
Inline: False
Direct callers:
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff814e7f50-ffffffff814e824b: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815148d0)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff815148d0-ffffffff81514bc8: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81535310)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff81535310-ffffffff81535608: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81599790)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff81599790-ffffffff81599a91: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815b51a0)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff815b51a0-ffffffff815b549c: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815bffe0)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff815bffe0-ffffffff815c02c1: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff816279b0)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff816279b0-ffffffff81627d4d: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff816f8580)
Location: lib/assoc_array.c:1078
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff816f8580-ffffffff816f8942: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff817eae10)
Location: lib/assoc_array.c:1078
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff817eae10-ffffffff817eb1d2: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8182afa0)
Location: lib/assoc_array.c:1078
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff8182afa0-ffffffff8182b362: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8187cad0)
Location: lib/assoc_array.c:1078
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff8187cad0-ffffffff8187cef0: assoc_array_delete (STB_GLOBAL)
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
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffff800010641b88)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffff800010641b88-ffff800010641e34: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (c07e7598)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
c07e7598-c07e7858: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (c0000000007ec730)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:__key_unlink_begin
```
**Symbols:**

```
c0000000007ec730-c0000000007ecac0: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffe00046e094)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffe00046e094-ffffffe00046e298: assoc_array_delete (STB_GLOBAL)
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
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8152d8f0)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff8152d8f0-ffffffff8152dbe8: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8151dbd0)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff8151dbd0-ffffffff8151dec8: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81529980)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff81529980-ffffffff81529c78: assoc_array_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct assoc_array_edit *assoc_array_delete(struct assoc_array *array, const struct assoc_array_ops *ops, const void *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81543360)
Location: lib/assoc_array.c:1079
Inline: False
Direct callers:
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
```
**Symbols:**

```
ffffffff81543360-ffffffff81543658: assoc_array_delete (STB_GLOBAL)
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
