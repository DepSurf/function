# Function: <code>__crypto_dh_decode_key</code>

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
int __crypto_dh_decode_key(const char *buf, unsigned int len, struct dh *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff81654740)
Location: crypto/dh_helper.c:66
Inline: False
Direct callers:
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh_helper.c:crypto_dh_decode_key
```
**Symbols:**

```
ffffffff81654740-ffffffff816547ca: __crypto_dh_decode_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __crypto_dh_decode_key(const char *buf, unsigned int len, struct dh *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8170e780)
Location: crypto/dh_helper.c:66
Inline: False
Direct callers:
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh_helper.c:crypto_dh_decode_key
```
**Symbols:**

```
ffffffff8170e780-ffffffff8170e836: __crypto_dh_decode_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __crypto_dh_decode_key(const char *buf, unsigned int len, struct dh *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff817490d0)
Location: crypto/dh_helper.c:66
Inline: False
Direct callers:
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh_helper.c:crypto_dh_decode_key
```
**Symbols:**

```
ffffffff817490d0-ffffffff81749192: __crypto_dh_decode_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __crypto_dh_decode_key(const char *buf, unsigned int len, struct dh *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8178af70)
Location: crypto/dh_helper.c:66
Inline: False
Direct callers:
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh_helper.c:crypto_dh_decode_key
```
**Symbols:**

```
ffffffff8178af70-ffffffff8178b032: __crypto_dh_decode_key (STB_GLOBAL)
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
