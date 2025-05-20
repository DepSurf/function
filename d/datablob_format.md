# Function: <code>datablob_format</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8133990b)
Location: security/keys/encrypted-keys/encrypted.c:275
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136eff9)
Location: security/keys/encrypted-keys/encrypted.c:275
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81385829)
Location: security/keys/encrypted-keys/encrypted.c:275
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8139a083)
Location: security/keys/encrypted-keys/encrypted.c:269
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf713)
Location: security/keys/encrypted-keys/encrypted.c:269
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813f04d8)
Location: security/keys/encrypted-keys/encrypted.c:269
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b7b8)
Location: security/keys/encrypted-keys/encrypted.c:273
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81438503)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814522d0)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4040)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff814a4040-ffffffff814a40e3: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1840)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff814c1840-ffffffff814c18e3: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c7cc0)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff814c7cc0-ffffffff814c7d63: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff815207b0)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff815207b0-ffffffff81520855: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b3ee0)
Location: security/keys/encrypted-keys/encrypted.c:276
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff815b3ee0-ffffffff815b3f9e: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165ec60)
Location: security/keys/encrypted-keys/encrypted.c:276
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff8165ec60-ffffffff8165ed1e: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff816975b0)
Location: security/keys/encrypted-keys/encrypted.c:276
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff816975b0-ffffffff8169766e: datablob_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *datablob_format(struct encrypted_key_payload *epayload, size_t asciiblob_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3c30)
Location: security/keys/encrypted-keys/encrypted.c:276
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
**Symbols:**

```
ffffffff816d3c30-ffffffff816d3cee: datablob_format (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffff80001053dc9c)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c06f3440)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c00000000068d0b0)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039b114)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a8b0)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b300)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446950)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145dc80)
Location: security/keys/encrypted-keys/encrypted.c:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
</details>
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
