# Function: <code>search_process_keyrings_rcu</code>

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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81431000)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff81431000-ffffffff814310bf: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8144ad60)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff8144ad60-ffffffff8144ae1f: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8149c950)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff8149c950-ffffffff8149ca0f: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814ba3f0)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff814ba3f0-ffffffff814ba4af: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814c0270)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff814c0270-ffffffff814c032f: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81518c90)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff81518c90-ffffffff81518d4f: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff815ab830)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff815ab830-ffffffff815ab8fa: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81655c90)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff81655c90-ffffffff81655d5a: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8168e4c0)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff8168e4c0-ffffffff8168e58a: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff816caa10)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff816caa10-ffffffff816caada: search_process_keyrings_rcu (STB_GLOBAL)
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffff800010534a50)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffff800010534a50-ffff800010534b34: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (c06ec104)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
c06ec104-c06ec1d8: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (c000000000682d80)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
c000000000682d80-c000000000682e9c: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffe000394b4c)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffe000394b4c-ffffffe000394bfe: search_process_keyrings_rcu (STB_GLOBAL)
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81443340)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff81443340-ffffffff814433ff: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81433d90)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff81433d90-ffffffff81433e4f: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143f4e0)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff8143f4e0-ffffffff8143f59f: search_process_keyrings_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
key_ref_t search_process_keyrings_rcu(struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81456680)
Location: security/keys/process_keys.c:539
Inline: False
Direct callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
**Symbols:**

```
ffffffff81456680-ffffffff8145673f: search_process_keyrings_rcu (STB_GLOBAL)
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
