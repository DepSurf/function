# Function: <code>request_master_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81338cf0)
Location: security/keys/encrypted-keys/encrypted.c:428
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81338cf0-ffffffff81338dc3: request_master_key.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e300)
Location: security/keys/encrypted-keys/encrypted.c:437
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8136e300-ffffffff8136e3d3: request_master_key.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384b20)
Location: security/keys/encrypted-keys/encrypted.c:437
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81384b20-ffffffff81384bf3: request_master_key.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399170)
Location: security/keys/encrypted-keys/encrypted.c:415
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81399170-ffffffff81399266: request_master_key.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813be960)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813be960-ffffffff813bea79: request_master_key.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813ef7c0-ffffffff813ef8bd: request_master_key.isra.5 (STB_LOCAL)
ffffffff813f0b38-ffffffff813f0b62: request_master_key.isra.5.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:426
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8140aa10-ffffffff8140ab0d: request_master_key.isra.5 (STB_LOCAL)
ffffffff8140be18-ffffffff8140be42: request_master_key.isra.5.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81437c20-ffffffff81437d07: request_master_key.isra.0 (STB_LOCAL)
ffffffff81438f64-ffffffff81438fac: request_master_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81451950-ffffffff81451a37: request_master_key.isra.0 (STB_LOCAL)
ffffffff81452db6-ffffffff81452dfe: request_master_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:410
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff814a3ee0-ffffffff814a3fc8: request_master_key (STB_LOCAL)
ffffffff814a5556-ffffffff814a55a0: request_master_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:410
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff814c1700-ffffffff814c17e8: request_master_key (STB_LOCAL)
ffffffff81befde9-ffffffff81befe33: request_master_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:410
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff814c7bd0-ffffffff814c7cb8: request_master_key (STB_LOCAL)
ffffffff81be1e4c-ffffffff81be1e96: request_master_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:410
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff815206c0-ffffffff815207a8: request_master_key (STB_LOCAL)
ffffffff81cd30bd-ffffffff81cd3107: request_master_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:416
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff815b3de0-ffffffff815b3edf: request_master_key (STB_LOCAL)
ffffffff81e8626d-ffffffff81e862b8: request_master_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165eb10)
Location: security/keys/encrypted-keys/encrypted.c:416
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff8165eb10-ffffffff8165ec4d: request_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697460)
Location: security/keys/encrypted-keys/encrypted.c:416
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff81697460-ffffffff8169759e: request_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3ae0)
Location: security/keys/encrypted-keys/encrypted.c:416
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
```
**Symbols:**

```
ffffffff816d3ae0-ffffffff816d3c1e: request_master_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffff80001053c9a0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffff80001053c9a0-ffff80001053cad8: request_master_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *request_master_key(struct encrypted_key_payload *epayload, const u8 **master_key, size_t *master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c06f2740)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
c06f2740-c06f2858: request_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c00000000068c3b0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
c00000000068c3b0-c00000000068c618: request_master_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a5d4)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffe00039a5d4-ffffffe00039a6e8: request_master_key.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81449f30-ffffffff8144a017: request_master_key.isra.0 (STB_LOCAL)
ffffffff8144b396-ffffffff8144b3de: request_master_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8143a980-ffffffff8143aa67: request_master_key.isra.0 (STB_LOCAL)
ffffffff8143bde6-ffffffff8143be2e: request_master_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81445fd0-ffffffff814460b7: request_master_key.isra.0 (STB_LOCAL)
ffffffff81447436-ffffffff8144747e: request_master_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:422
Inline: True
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8145d300-ffffffff8145d3e7: request_master_key.isra.0 (STB_LOCAL)
ffffffff8145e766-ffffffff8145e7ae: request_master_key.isra.0.cold (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
