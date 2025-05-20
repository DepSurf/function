# Function: <code>keyring_search_rcu</code>

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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142d760)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff8142d760-ffffffff8142d7f7: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814474b0)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff814474b0-ffffffff81447547: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81498c00)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff81498c00-ffffffff81498cb8: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b6670)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff814b6670-ffffffff814b6728: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bc4c0)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff814bc4c0-ffffffff814bc578: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81514ee0)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff81514ee0-ffffffff81514f98: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a7650)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff815a7650-ffffffff815a771c: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81651680)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff81651680-ffffffff8165174c: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81689f30)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff81689f30-ffffffff81689ffc: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c6430)
Location: security/keys/keyring.c:899
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff816c6430-ffffffff816c64fc: keyring_search_rcu (STB_GLOBAL)
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff800010530c78)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffff800010530c78-ffff800010530d4c: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e8af0)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
c06e8af0-c06e8ba4: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067ded0)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
c00000000067ded0-c00000000067dfd4: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe000391dea)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffe000391dea-ffffffe000391e8a: keyring_search_rcu (STB_GLOBAL)
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143fa90)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff8143fa90-ffffffff8143fb27: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81430500)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff81430500-ffffffff81430597: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143bc30)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff8143bc30-ffffffff8143bcc7: keyring_search_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81452da0)
Location: security/keys/keyring.c:903
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_search
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
```
**Symbols:**

```
ffffffff81452da0-ffffffff81452e37: keyring_search_rcu (STB_GLOBAL)
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
