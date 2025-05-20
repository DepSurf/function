# Function: <code>__dh_safe_prime_create</code>

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
int __dh_safe_prime_create(struct crypto_template *tmpl, struct rtattr **tb, const struct dh_safe_prime *safe_prime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff81653f40)
Location: crypto/dh.c:548
Inline: False
Direct callers:
  - crypto/dh.c:dh_ffdhe8192_create
  - crypto/dh.c:dh_ffdhe6144_create
  - crypto/dh.c:dh_ffdhe4096_create
  - crypto/dh.c:dh_ffdhe3072_create
  - crypto/dh.c:dh_ffdhe2048_create
```
**Symbols:**

```
ffffffff81653f40-ffffffff81654118: __dh_safe_prime_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dh_safe_prime_create(struct crypto_template *tmpl, struct rtattr **tb, const struct dh_safe_prime *safe_prime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff8170dec0)
Location: crypto/dh.c:551
Inline: False
Direct callers:
  - crypto/dh.c:dh_ffdhe8192_create
  - crypto/dh.c:dh_ffdhe6144_create
  - crypto/dh.c:dh_ffdhe4096_create
  - crypto/dh.c:dh_ffdhe3072_create
  - crypto/dh.c:dh_ffdhe2048_create
```
**Symbols:**

```
ffffffff8170dec0-ffffffff8170e08e: __dh_safe_prime_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dh_safe_prime_create(struct crypto_template *tmpl, struct rtattr **tb, const struct dh_safe_prime *safe_prime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff817485f0)
Location: crypto/dh.c:550
Inline: False
Direct callers:
  - crypto/dh.c:dh_ffdhe8192_create
  - crypto/dh.c:dh_ffdhe6144_create
  - crypto/dh.c:dh_ffdhe4096_create
  - crypto/dh.c:dh_ffdhe3072_create
  - crypto/dh.c:dh_ffdhe2048_create
```
**Symbols:**

```
ffffffff817485f0-ffffffff817487c4: __dh_safe_prime_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dh_safe_prime_create(struct crypto_template *tmpl, struct rtattr **tb, const struct dh_safe_prime *safe_prime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff8178a460)
Location: crypto/dh.c:550
Inline: False
Direct callers:
  - crypto/dh.c:dh_ffdhe8192_create
  - crypto/dh.c:dh_ffdhe6144_create
  - crypto/dh.c:dh_ffdhe4096_create
  - crypto/dh.c:dh_ffdhe3072_create
  - crypto/dh.c:dh_ffdhe2048_create
```
**Symbols:**

```
ffffffff8178a460-ffffffff8178a663: __dh_safe_prime_create (STB_LOCAL)
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
