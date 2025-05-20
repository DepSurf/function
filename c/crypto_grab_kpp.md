# Function: <code>crypto_grab_kpp</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_grab_kpp(struct crypto_kpp_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff816538e0)
Location: crypto/kpp.c:98
Inline: False
Direct callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff816538e0-ffffffff81653907: crypto_grab_kpp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_grab_kpp(struct crypto_kpp_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff8170d7b0)
Location: crypto/kpp.c:98
Inline: False
Direct callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff8170d7b0-ffffffff8170d7d7: crypto_grab_kpp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_grab_kpp(struct crypto_kpp_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff81748030)
Location: crypto/kpp.c:117
Inline: False
Direct callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff81748030-ffffffff81748057: crypto_grab_kpp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_grab_kpp(struct crypto_kpp_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff81789ea0)
Location: crypto/kpp.c:117
Inline: False
Direct callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff81789ea0-ffffffff81789ec7: crypto_grab_kpp (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
