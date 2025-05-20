# Function: <code>x509_note_sig_algo</code>

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
int x509_note_sig_algo(void *context, size_t hdrlen, unsigned char tag, const void *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8166ad30)
Location: crypto/asymmetric_keys/x509_cert_parser.c:190
Inline: False
```
**Symbols:**

```
ffffffff8166ad30-ffffffff8166af91: x509_note_sig_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x509_note_sig_algo(void *context, size_t hdrlen, unsigned char tag, const void *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817257f0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:190
Inline: False
```
**Symbols:**

```
ffffffff817257f0-ffffffff81725a51: x509_note_sig_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x509_note_sig_algo(void *context, size_t hdrlen, unsigned char tag, const void *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81761ac0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:190
Inline: False
```
**Symbols:**

```
ffffffff81761ac0-ffffffff81761d0e: x509_note_sig_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x509_note_sig_algo(void *context, size_t hdrlen, unsigned char tag, const void *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817a3510)
Location: crypto/asymmetric_keys/x509_cert_parser.c:190
Inline: False
```
**Symbols:**

```
ffffffff817a3510-ffffffff817a37cd: x509_note_sig_algo (STB_GLOBAL)
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
