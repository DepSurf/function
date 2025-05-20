# Function: <code>__key_link_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81331980)
Location: security/keys/keyring.c:1071
Inline: True
Direct callers:
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81331980-ffffffff81331a74: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81366720)
Location: security/keys/keyring.c:1095
Inline: True
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81366720-ffffffff81366826: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137cf40)
Location: security/keys/keyring.c:1095
Inline: True
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff8137cf40-ffffffff8137d046: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81390cb0)
Location: security/keys/keyring.c:1207
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff81390cb0-ffffffff81390da7: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b62a0)
Location: security/keys/keyring.c:1209
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff813b62a0-ffffffff813b639a: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e6aa0)
Location: security/keys/keyring.c:1202
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff813e6aa0-ffffffff813e6b9a: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814012a0)
Location: security/keys/keyring.c:1200
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:request_key_and_link
```
**Symbols:**

```
ffffffff814012a0-ffffffff8140139a: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142dba0)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8142dba0-ffffffff8142dc3f: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814478f0)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff814478f0-ffffffff8144798f: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814990a0)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff814990a0-ffffffff8149913f: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b6b20)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff814b6b20-ffffffff814b6bbf: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bc960)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff814bc960-ffffffff814bc9ff: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81515380)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff81515380-ffffffff8151541f: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a7b50)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff815a7b50-ffffffff815a7bfa: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81651be0)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff81651be0-ffffffff81651c8a: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8168a480)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff8168a480-ffffffff8168a52a: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c6980)
Location: security/keys/keyring.c:1292
Inline: False
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff816c6980-ffffffff816c6a2a: __key_link_begin (STB_GLOBAL)
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
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff800010531190)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffff800010531190-ffff800010531258: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e8f58)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
c06e8f58-c06e9014: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067e740)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
c00000000067e740-c00000000067e888: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe0003921fc)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffe0003921fc-ffffffe0003922a0: __key_link_begin (STB_GLOBAL)
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
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143fed0)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8143fed0-ffffffff8143ff6f: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81430940)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff81430940-ffffffff814309df: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143c070)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8143c070-ffffffff8143c10f: __key_link_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __key_link_begin(struct key *keyring, const struct keyring_index_key *index_key, struct assoc_array_edit **_edit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814531f0)
Location: security/keys/keyring.c:1294
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff814531f0-ffffffff8145328f: __key_link_begin (STB_GLOBAL)
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
