# Function: <code>crypto_cbc_exit_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_tfm *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813a9210)
Location: crypto/cbc.c:208
Inline: False
```
**Symbols:**

```
ffffffff813a9210-ffffffff813a9227: crypto_cbc_exit_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_tfm *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813e71d0)
Location: crypto/cbc.c:208
Inline: False
```
**Symbols:**

```
ffffffff813e71d0-ffffffff813e71e7: crypto_cbc_exit_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_skcipher *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813fffb0)
Location: crypto/cbc.c:95
Inline: False
```
**Symbols:**

```
ffffffff813fffb0-ffffffff813fffc7: crypto_cbc_exit_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_skcipher *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8140d2c0)
Location: crypto/cbc.c:96
Inline: False
```
**Symbols:**

```
ffffffff8140d2c0-ffffffff8140d2d7: crypto_cbc_exit_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_skcipher *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81435d30)
Location: crypto/cbc.c:96
Inline: False
```
**Symbols:**

```
ffffffff81435d30-ffffffff81435d47: crypto_cbc_exit_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_skcipher *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814688c0)
Location: crypto/cbc.c:96
Inline: False
```
**Symbols:**

```
ffffffff814688c0-ffffffff814688d7: crypto_cbc_exit_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_cbc_exit_tfm(struct crypto_skcipher *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81486530)
Location: crypto/cbc.c:96
Inline: False
```
**Symbols:**

```
ffffffff81486530-ffffffff81486547: crypto_cbc_exit_tfm (STB_LOCAL)
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
<code>struct crypto_tfm *tfm</code> ➡️ <code>struct crypto_skcipher *tfm</code>
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
