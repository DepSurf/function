# Function: <code>fsverity_msg</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff813506bb)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff813506bb-ffffffff8135078f: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff8139709e)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:ensure_verity_info
  - fs/verity/open.c:ensure_verity_info
  - fs/verity/open.c:ensure_verity_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff8139709e-ffffffff81397172: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81beb4c7)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:ensure_verity_info
  - fs/verity/open.c:ensure_verity_info
  - fs/verity/open.c:ensure_verity_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81beb4c7-ffffffff81beb59b: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81bdd51b)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81bdd51b-ffffffff81bdd5ef: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81cc6e21)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81cc6e21-ffffffff81cc6ef5: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81e7935d)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81e7935d-ffffffff81e79464: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81505380)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81505380-ffffffff815054a0: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff8153c5a0)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:write_merkle_tree_block
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff8153c5a0-ffffffff8153c6c0: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81571860)
Location: fs/verity/init.c:42
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:write_merkle_tree_block
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_get_descriptor
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81571860-ffffffff81571980: fsverity_msg (STB_GLOBAL)
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
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffff800010412288)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffff800010412288-ffff800010412364: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (c05de8dc)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
c05de8dc-c05de9ac: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (c000000000520000)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
c000000000520000-c000000000520108: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffe0002ba2b6)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffe0002ba2b6-ffffffe0002ba356: fsverity_msg (STB_GLOBAL)
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
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81348c9b)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81348c9b-ffffffff81348d6f: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff8133997b)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff8133997b-ffffffff81339a4f: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff8134676b)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff8134676b-ffffffff8134683f: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsverity_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/init.c (ffffffff81359a4b)
Location: fs/verity/init.c:12
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/open.c:fsverity_init_merkle_tree_params
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/verity/signature.c:fsverity_verify_signature
```
**Symbols:**

```
ffffffff81359a4b-ffffffff81359b1f: fsverity_msg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
