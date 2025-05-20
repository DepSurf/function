# Function: <code>dump_security_xattr</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dump_security_xattr(const char *prefix, const void *src, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff815a31b0)
Location: security/integrity/evm/evm_crypto.c:189
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff815a31b0-ffffffff815a3229: dump_security_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dump_security_xattr(const char *prefix, const void *src, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff816499f0)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff816499f0-ffffffff81649a7a: dump_security_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dump_security_xattr(const char *prefix, const void *src, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81702a10)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81702a10-ffffffff81702a9a: dump_security_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dump_security_xattr(const char *name, const char *value, size_t value_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8173cde0)
Location: security/integrity/evm/evm_crypto.c:203
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8173cde0-ffffffff8173ced3: dump_security_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dump_security_xattr(const char *name, const char *value, size_t value_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8177dc80)
Location: security/integrity/evm/evm_crypto.c:203
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8177dc80-ffffffff8177dcf1: dump_security_xattr (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param added. </b>
<code>const char *value</code>
</li>
<li>
<b>Param added. </b>
<code>size_t value_len</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *prefix</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
