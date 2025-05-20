# Function: <code>crypto_cbc_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crypto_cbc_free(struct crypto_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813a91e0)
Location: crypto/cbc.c:264
Inline: False
```
**Symbols:**

```
ffffffff813a91e0-ffffffff813a9204: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crypto_cbc_free(struct crypto_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813e71a0)
Location: crypto/cbc.c:264
Inline: False
```
**Symbols:**

```
ffffffff813e71a0-ffffffff813e71c4: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_cbc_free(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813fff80)
Location: crypto/cbc.c:102
Inline: False
```
**Symbols:**

```
ffffffff813fff80-ffffffff813fffa4: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crypto_cbc_free(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8140d290)
Location: crypto/cbc.c:103
Inline: False
```
**Symbols:**

```
ffffffff8140d290-ffffffff8140d2b4: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crypto_cbc_free(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81435d00)
Location: crypto/cbc.c:103
Inline: False
```
**Symbols:**

```
ffffffff81435d00-ffffffff81435d24: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crypto_cbc_free(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81468890)
Location: crypto/cbc.c:103
Inline: False
```
**Symbols:**

```
ffffffff81468890-ffffffff814688b4: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_cbc_free(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81486500)
Location: crypto/cbc.c:103
Inline: False
```
**Symbols:**

```
ffffffff81486500-ffffffff81486524: crypto_cbc_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct crypto_instance *inst</code> ➡️ <code>struct skcipher_instance *inst</code>
</li>
</ul>
</details>
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
</ul>
