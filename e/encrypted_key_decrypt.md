# Function: <code>encrypted_key_decrypt</code>

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
In security/keys/encrypted-keys/encrypted.c (ffffffff81339c26)
Location: security/keys/encrypted-keys/encrypted.c:651
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8136f306)
Location: security/keys/encrypted-keys/encrypted.c:672
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81385b36)
Location: security/keys/encrypted-keys/encrypted.c:672
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8139a3d4)
Location: security/keys/encrypted-keys/encrypted.c:653
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff813bfa64)
Location: security/keys/encrypted-keys/encrypted.c:660
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff813f0834)
Location: security/keys/encrypted-keys/encrypted.c:660
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8140bb14)
Location: security/keys/encrypted-keys/encrypted.c:671
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81438bed)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81452a2d)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:655
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814a51c0-ffffffff814a5355: encrypted_key_decrypt (STB_LOCAL)
ffffffff814a578c-ffffffff814a57b6: encrypted_key_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:655
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814c2990-ffffffff814c2b25: encrypted_key_decrypt (STB_LOCAL)
ffffffff81bf001f-ffffffff81bf0049: encrypted_key_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:655
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814c89b0-ffffffff814c8b45: encrypted_key_decrypt (STB_LOCAL)
ffffffff81be203d-ffffffff81be2067: encrypted_key_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:655
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff815218d0-ffffffff81521a65: encrypted_key_decrypt (STB_LOCAL)
ffffffff81cd32c2-ffffffff81cd32ec: encrypted_key_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:681
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff815b5290-ffffffff815b5468: encrypted_key_decrypt (STB_LOCAL)
ffffffff81e8648a-ffffffff81e864b0: encrypted_key_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff816602a0)
Location: security/keys/encrypted-keys/encrypted.c:681
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff816602a0-ffffffff8166048e: encrypted_key_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81698be0)
Location: security/keys/encrypted-keys/encrypted.c:681
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81698be0-ffffffff81698dce: encrypted_key_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int encrypted_key_decrypt(struct encrypted_key_payload *epayload, const char *format, const char *hex_encoded_iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d5290)
Location: security/keys/encrypted-keys/encrypted.c:681
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff816d5290-ffffffff816d547e: encrypted_key_decrypt (STB_LOCAL)
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
In security/keys/encrypted-keys/encrypted.c (ffff80001053d8ec)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (c06f3b4c)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (c00000000068dd8c)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffe00039b3de)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8144b00d)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8143ba5d)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814470ad)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8145e3dd)
Location: security/keys/encrypted-keys/encrypted.c:667
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
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
