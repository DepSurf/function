# Function: <code>crypto_grab_shash</code>

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
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815253c0)
Location: crypto/shash.c:496
Inline: False
```
**Symbols:**

```
ffffffff815253c0-ffffffff815253d8: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815422e0)
Location: crypto/shash.c:496
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff815422e0-ffffffff815422f8: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154a980)
Location: crypto/shash.c:508
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff8154a980-ffffffff8154a998: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab160)
Location: crypto/shash.c:508
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff815ab160-ffffffff815ab178: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff816528c0)
Location: crypto/shash.c:508
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff816528c0-ffffffff816528e7: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c020)
Location: crypto/shash.c:498
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff8170c020-ffffffff8170c047: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745a20)
Location: crypto/shash.c:563
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff81745a20-ffffffff81745a47: crypto_grab_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_grab_shash(struct crypto_shash_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81788390)
Location: crypto/shash.c:293
Inline: False
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff81788390-ffffffff817883b7: crypto_grab_shash (STB_GLOBAL)
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
