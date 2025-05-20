# Function: <code>__key_link_lock</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142da90)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8142da90-ffffffff8142dae9: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814477e0)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff814477e0-ffffffff81447839: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8149931c)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff81498f90-ffffffff81498fe7: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b6d9c)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff814b6a10-ffffffff814b6a67: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bcbdc)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff814bc850-ffffffff814bc8a7: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815155fc)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff81515270-ffffffff815152c7: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a7e1b)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff815a7a20-ffffffff815a7a87: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81651eeb)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff81651a90-ffffffff81651af7: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8168a78b)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff8168a340-ffffffff8168a3a7: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c6c8b)
Location: security/keys/keyring.c:1236
Inline: True
Inline callers:
  - security/keys/keyring.c:key_link
Direct callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/request_key.c:construct_alloc_key
```
**Symbols:**

```
ffffffff816c6840-ffffffff816c68a7: __key_link_lock (STB_GLOBAL)
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
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff800010531038)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffff800010531038-ffff8000105310bc: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e8e58)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
c06e8e58-c06e8eb8: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067e560)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
c00000000067e560-c00000000067e618: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe0003920d8)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffe0003920d8-ffffffe00039214e: __key_link_lock (STB_GLOBAL)
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
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143fdc0)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8143fdc0-ffffffff8143fe19: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81430830)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff81430830-ffffffff81430889: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143bf60)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff8143bf60-ffffffff8143bfb9: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __key_link_lock(struct key *keyring, const struct keyring_index_key *index_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814530e0)
Location: security/keys/keyring.c:1238
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_instantiate_and_link
  - security/keys/keyring.c:key_link
  - security/keys/request_key.c:construct_key_and_link
```
**Symbols:**

```
ffffffff814530e0-ffffffff81453139: __key_link_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
