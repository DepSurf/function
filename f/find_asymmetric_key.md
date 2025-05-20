# Function: <code>find_asymmetric_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff813eff30)
Location: crypto/asymmetric_keys/asymmetric_type.c:48
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff813eff30-ffffffff813f013c: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814097b0)
Location: crypto/asymmetric_keys/asymmetric_type.c:48
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814097b0-ffffffff814099bc: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81416d10)
Location: crypto/asymmetric_keys/asymmetric_type.c:49
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81416d10-ffffffff81416ed4: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81441740)
Location: crypto/asymmetric_keys/asymmetric_type.c:49
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81441740-ffffffff8144190b: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814745f0)
Location: crypto/asymmetric_keys/asymmetric_type.c:49
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814745f0-ffffffff814747a5: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81492230)
Location: crypto/asymmetric_keys/asymmetric_type.c:50
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81492230-ffffffff814923e5: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814bff40)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814bff40-ffffffff814c0111: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d8d90)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814d8d90-ffffffff814d8f61: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81538000)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81538000-ffffffff815381ce: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81554e60)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81554e60-ffffffff8155502e: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8155d5d0)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff8155d5d0-ffffffff8155d7aa: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815be8f0)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff815be8f0-ffffffff815beaba: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, const struct asymmetric_key_id *id_2, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81668260)
Location: crypto/asymmetric_keys/asymmetric_type.c:52
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81668260-ffffffff816684b6: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, const struct asymmetric_key_id *id_2, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81722910)
Location: crypto/asymmetric_keys/asymmetric_type.c:52
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81722910-ffffffff81722b66: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, const struct asymmetric_key_id *id_2, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8175ec90)
Location: crypto/asymmetric_keys/asymmetric_type.c:51
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff8175ec90-ffffffff8175eed4: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, const struct asymmetric_key_id *id_2, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817a0480)
Location: crypto/asymmetric_keys/asymmetric_type.c:51
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff817a0480-ffffffff817a06c4: find_asymmetric_key (STB_GLOBAL)
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
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffff8000105d48e0)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffff8000105d48e0-ffff8000105d4af4: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (c078224c)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
c078224c-c0782420: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (c000000000762f30)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
c000000000762f30-c000000000763210: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffe000418bf2)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffe000418bf2-ffffffe000418dda: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d1370)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814d1370-ffffffff814d1541: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c1d90)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814c1d90-ffffffff814c1f61: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814cd400)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814cd400-ffffffff814cd5d1: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *find_asymmetric_key(struct key *keyring, const struct asymmetric_key_id *id_0, const struct asymmetric_key_id *id_1, bool partial);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814e5ed0)
Location: crypto/asymmetric_keys/asymmetric_type.c:46
Inline: False
Direct callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814e5ed0-ffffffff814e60a1: find_asymmetric_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct asymmetric_key_id *id_2</code>
</li>
<li>
<b>Param reordered. </b>
<code>keyring, id_0, id_1, partial</code> ➡️ <code>keyring, id_0, id_1, id_2, partial</code>
</li>
</ul>
</details>
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
