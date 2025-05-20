# Function: <code>ima_post_key_create_or_update</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff8151caf0)
Location: security/integrity/ima/ima_asymmetric_keys.c:27
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
**Symbols:**

```
ffffffff8151caf0-ffffffff8151cb5e: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff81539920)
Location: security/integrity/ima/ima_asymmetric_keys.c:27
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
**Symbols:**

```
ffffffff81539920-ffffffff81539993: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff81542020)
Location: security/integrity/ima/ima_asymmetric_keys.c:28
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
**Symbols:**

```
ffffffff81542020-ffffffff815420a0: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff815a1f80)
Location: security/integrity/ima/ima_asymmetric_keys.c:29
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
**Symbols:**

```
ffffffff815a1f80-ffffffff815a2004: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff816483b0)
Location: security/integrity/ima/ima_asymmetric_keys.c:29
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
**Symbols:**

```
ffffffff816483b0-ffffffff8164845c: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff81701090)
Location: security/integrity/ima/ima_asymmetric_keys.c:29
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
**Symbols:**

```
ffffffff81701090-ffffffff8170113c: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff8173b130)
Location: security/integrity/ima/ima_asymmetric_keys.c:29
Inline: False
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
**Symbols:**

```
ffffffff8173b130-ffffffff8173b1dc: ima_post_key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ima_post_key_create_or_update(struct key *keyring, struct key *key, const void *payload, size_t payload_len, long unsigned int flags, bool create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_asymmetric_keys.c (ffffffff8177bcc0)
Location: security/integrity/ima/ima_asymmetric_keys.c:29
Inline: False
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
**Symbols:**

```
ffffffff8177bcc0-ffffffff8177bd6c: ima_post_key_create_or_update (STB_GLOBAL)
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
