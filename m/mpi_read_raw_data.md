# Function: <code>mpi_read_raw_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81416a30)
Location: lib/mpi/mpicoder.c:32
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/x509_cert_parser.c:rsa_extract_mpi
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
```
**Symbols:**

```
ffffffff81416a30-ffffffff81416b2c: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8145e740)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - security/keys/dh.c:mpi_from_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8145e740-ffffffff8145e846: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8147d210)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - security/keys/dh.c:mpi_from_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8147d210-ffffffff8147d316: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814864f0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff814864f0-ffffffff81486607: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814c2670)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff814c2670-ffffffff814c2787: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff814f3dba-ffffffff814f3dcf: mpi_read_raw_data.cold.2 (STB_LOCAL)
ffffffff814f35b0-ffffffff814f36bb: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8150810e-ffffffff81508123: mpi_read_raw_data.cold.2 (STB_LOCAL)
ffffffff815078e0-ffffffff815079eb: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff81536268-ffffffff8153627e: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff81535ad0-ffffffff81535bdd: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff81557078-ffffffff8155708e: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff815568e0-ffffffff815569ed: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff815e091c-ffffffff815e0933: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff815e0180-ffffffff815e0293: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff81bf4839-ffffffff81bf4850: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff81601580-ffffffff81601698: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff81be6731-ffffffff81be6748: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff815e4310-ffffffff815e4428: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff81cde147-ffffffff81cde15e: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff81650540-ffffffff81650658: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff81ea44ad-ffffffff81ea44c0: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff817674b0-ffffffff817675d7: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818967a0)
Location: lib/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff818967a0-ffffffff818968d5: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818d8c60)
Location: lib/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff818d8c60-ffffffff818d8d95: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpicoder.c (ffffffff8186f7c0)
Location: lib/crypto/mpi/mpicoder.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/crypto/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8186f7c0-ffffffff8186f8f5: mpi_read_raw_data (STB_GLOBAL)
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
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffff8000106630f0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffff8000106630f0-ffff800010663230: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (c080bcc4)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
c080bcc4-c080bdbc: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (c000000000817770)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
c000000000817770-c000000000817920: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffe00048fbb4)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffe00048fbb4-ffffffe00048fcce: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8154f658-ffffffff8154f66e: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff8154eec0-ffffffff8154efcd: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8153f938-ffffffff8153f94e: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff8153f1a0-ffffffff8153f2ad: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff8154b398-ffffffff8154b3ae: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff8154ac00-ffffffff8154ad0d: mpi_read_raw_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
MPI mpi_read_raw_data(const void *xbuffer, size_t nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpicoder.c (0)
Location: lib/mpi/mpicoder.c:35
Inline: False
Direct callers:
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/dh.c:dh_set_secret
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
```
**Symbols:**

```
ffffffff815651e8-ffffffff815651fe: mpi_read_raw_data.cold (STB_LOCAL)
ffffffff81564a50-ffffffff81564b5d: mpi_read_raw_data (STB_GLOBAL)
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
