# Function: <code>encrypted_key_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81339350)
Location: security/keys/encrypted-keys/encrypted.c:598
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81339350-ffffffff81339510: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136ea30)
Location: security/keys/encrypted-keys/encrypted.c:619
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8136ea30-ffffffff8136ebf7: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384d90)
Location: security/keys/encrypted-keys/encrypted.c:619
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81384d90-ffffffff81384f57: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399410)
Location: security/keys/encrypted-keys/encrypted.c:600
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81399410-ffffffff81399625: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bec20)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813bec20-ffffffff813bedfa: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813efa10-ffffffff813efbce: encrypted_key_alloc (STB_LOCAL)
ffffffff813f0bbf-ffffffff813f0bdd: encrypted_key_alloc.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:611
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8140ac60-ffffffff8140ae70: encrypted_key_alloc (STB_LOCAL)
ffffffff8140be9f-ffffffff8140bec9: encrypted_key_alloc.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81438710-ffffffff81438920: encrypted_key_alloc (STB_LOCAL)
ffffffff81439047-ffffffff81439071: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81452550-ffffffff8145275e: encrypted_key_alloc (STB_LOCAL)
ffffffff81452ea5-ffffffff81452ece: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:595
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814a4370-ffffffff814a4582: encrypted_key_alloc (STB_LOCAL)
ffffffff814a5664-ffffffff814a568d: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:595
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814c1b70-ffffffff814c1d82: encrypted_key_alloc (STB_LOCAL)
ffffffff81befef7-ffffffff81beff20: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:595
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814c7ff0-ffffffff814c81fb: encrypted_key_alloc (STB_LOCAL)
ffffffff81be1f29-ffffffff81be1f52: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:595
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81520ae0-ffffffff81520ceb: encrypted_key_alloc (STB_LOCAL)
ffffffff81cd319a-ffffffff81cd31c3: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen, const char *decrypted_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:601
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff815b4230-ffffffff815b449e: encrypted_key_alloc (STB_LOCAL)
ffffffff81e8634b-ffffffff81e863be: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen, const char *decrypted_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:601
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8165f0b0-ffffffff8165f397: encrypted_key_alloc (STB_LOCAL)
ffffffff82073197-ffffffff820731b2: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen, const char *decrypted_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:601
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81697a00-ffffffff81697cec: encrypted_key_alloc (STB_LOCAL)
ffffffff820f2e1d-ffffffff820f2e38: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen, const char *decrypted_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:601
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff816d4080-ffffffff816d436c: encrypted_key_alloc (STB_LOCAL)
ffffffff821d00b7-ffffffff821d00d2: encrypted_key_alloc.cold (STB_LOCAL)
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
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cbf0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffff80001053cbf0-ffff80001053ce14: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c06f36ac)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
c06f36ac-c06f38a0: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c00000000068d3b0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
c00000000068d3b0-c00000000068d8c8: encrypted_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039ac06)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffe00039ac06-ffffffe00039adcc: encrypted_key_alloc (STB_LOCAL)
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
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8144ab30-ffffffff8144ad3e: encrypted_key_alloc (STB_LOCAL)
ffffffff8144b485-ffffffff8144b4ae: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8143b580-ffffffff8143b78e: encrypted_key_alloc (STB_LOCAL)
ffffffff8143bed5-ffffffff8143befe: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81446bd0-ffffffff81446dde: encrypted_key_alloc (STB_LOCAL)
ffffffff81447525-ffffffff8144754e: encrypted_key_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct encrypted_key_payload *encrypted_key_alloc(struct key *key, const char *format, const char *master_desc, const char *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:607
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8145df00-ffffffff8145e10e: encrypted_key_alloc (STB_LOCAL)
ffffffff8145e855-ffffffff8145e87e: encrypted_key_alloc.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *decrypted_data</code>
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
