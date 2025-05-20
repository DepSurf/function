# Function: <code>shash_free_singlespawn_instance</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815254e0)
Location: crypto/shash.c:607
Inline: False
```
**Symbols:**

```
ffffffff815254e0-ffffffff81525508: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81542410)
Location: crypto/shash.c:607
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff81542410-ffffffff81542438: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154aab0)
Location: crypto/shash.c:619
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff8154aab0-ffffffff8154aad8: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab290)
Location: crypto/shash.c:619
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff815ab290-ffffffff815ab2b8: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652a30)
Location: crypto/shash.c:619
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff81652a30-ffffffff81652a5d: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c230)
Location: crypto/shash.c:618
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff8170c230-ffffffff8170c25d: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745b80)
Location: crypto/shash.c:737
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff81745b80-ffffffff81745bad: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shash_free_singlespawn_instance(struct shash_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff817884f0)
Location: crypto/shash.c:476
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff817884f0-ffffffff8178851d: shash_free_singlespawn_instance (STB_GLOBAL)
```
</details>
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
