# Function: <code>restrict_link_by_signature</code>

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
int restrict_link_by_signature(struct key *trust_keyring, const struct key_type *type, const union key_payload *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff813f03d0)
Location: crypto/asymmetric_keys/restrict.c:72
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff813f03d0-ffffffff813f0491: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *trust_keyring, const struct key_type *type, const union key_payload *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81409c50)
Location: crypto/asymmetric_keys/restrict.c:72
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81409c50-ffffffff81409d11: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81417740)
Location: crypto/asymmetric_keys/restrict.c:73
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81417740-ffffffff8141780b: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81442190)
Location: crypto/asymmetric_keys/restrict.c:74
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81442190-ffffffff8144226a: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81475070)
Location: crypto/asymmetric_keys/restrict.c:74
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81475070-ffffffff81475148: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81492cb0)
Location: crypto/asymmetric_keys/restrict.c:74
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81492cb0-ffffffff81492d88: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814c03a0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff814c03a0-ffffffff814c0485: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814d91f0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff814d91f0-ffffffff814d92d5: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff81538ac0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81538ac0-ffffffff81538ba5: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff815558c0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff815558c0-ffffffff815559a5: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff8155e030)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff8155e030-ffffffff8155e115: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81cd79b5-ffffffff81cd79ca: restrict_link_by_signature.cold (STB_LOCAL)
ffffffff815bf340-ffffffff815bf441: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff81e8ac02-ffffffff81e8ac17: restrict_link_by_signature.cold (STB_LOCAL)
ffffffff81669180-ffffffff816692aa: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff82075885-ffffffff8207589a: restrict_link_by_signature.cold (STB_LOCAL)
ffffffff817239e0-ffffffff81723b0a: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff820f5501-ffffffff820f5516: restrict_link_by_signature.cold (STB_LOCAL)
ffffffff8175fce0-ffffffff8175fe0a: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_secondary_and_machine
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_digsig
```
**Symbols:**

```
ffffffff821d2784-ffffffff821d2799: restrict_link_by_signature.cold (STB_LOCAL)
ffffffff817a1570-ffffffff817a169a: restrict_link_by_signature (STB_GLOBAL)
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
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffff8000105d5258)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffff8000105d5258-ffff8000105d535c: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (c0782ba4)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
c0782ba4-c0782c98: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (c0000000007635e0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
c0000000007635e0-c000000000763778: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffe0004194fe)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffe0004194fe-ffffffe0004195d6: restrict_link_by_signature (STB_GLOBAL)
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
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814d17d0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff814d17d0-ffffffff814d18b5: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814c21f0)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff814c21f0-ffffffff814c22d5: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814cd860)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff814cd860-ffffffff814cd945: restrict_link_by_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int restrict_link_by_signature(struct key *dest_keyring, const struct key_type *type, const union key_payload *payload, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/restrict.c (ffffffff814e6330)
Location: crypto/asymmetric_keys/restrict.c:70
Inline: False
Direct callers:
  - certs/system_keyring.c:restrict_link_by_builtin_and_secondary_trusted
  - certs/system_keyring.c:restrict_link_by_builtin_trusted
```
**Symbols:**

```
ffffffff814e6330-ffffffff814e6415: restrict_link_by_signature (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key *dest_keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>trust_keyring, type, payload</code> ➡️ <code>dest_keyring, type, payload, trust_keyring</code>
</li>
</ul>
</details>
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
