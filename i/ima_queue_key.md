# Function: <code>ima_queue_key</code>

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
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8151cd90)
Location: security/integrity/ima/ima_queue_keys.c:98
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff8151cd90-ffffffff8151ce2c: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff81539c30)
Location: security/integrity/ima/ima_queue_keys.c:103
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81539c30-ffffffff81539ccc: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff815420d0)
Location: security/integrity/ima/ima_queue_keys.c:104
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff815420d0-ffffffff81542275: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:104
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81cd743f-ffffffff81cd7453: ima_queue_key.cold (STB_LOCAL)
ffffffff815a2040-ffffffff815a21f1: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:104
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81e8a674-ffffffff81e8a689: ima_queue_key.cold (STB_LOCAL)
ffffffff816484a0-ffffffff8164863f: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:104
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff82075595-ffffffff820755aa: ima_queue_key.cold (STB_LOCAL)
ffffffff817011a0-ffffffff8170133f: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:104
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff820f50f7-ffffffff820f510c: ima_queue_key.cold (STB_LOCAL)
ffffffff8173b240-ffffffff8173b3df: ima_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ima_queue_key(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:104
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff821d22a1-ffffffff821d22b6: ima_queue_key.cold (STB_LOCAL)
ffffffff8177bdd0-ffffffff8177bf9e: ima_queue_key (STB_GLOBAL)
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
