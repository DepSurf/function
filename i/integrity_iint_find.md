# Function: <code>integrity_iint_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81396260)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81396260-ffffffff813962c9: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff813d1fd0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff813d1fd0-ffffffff813d2039: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff813e96f0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_main.c:ima_rdwr_violation_check
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff813e96f0-ffffffff813e9759: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff813f5b00)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_main.c:ima_rdwr_violation_check
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff813f5b00-ffffffff813f5b55: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8141dbf0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_main.c:ima_rdwr_violation_check
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff8141dbf0-ffffffff8141dc45: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8144fea0)
Location: security/integrity/iint.c:60
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8144fea0-ffffffff8144fef5: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8146ce80)
Location: security/integrity/iint.c:61
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8146ce80-ffffffff8146ced5: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8149a570)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8149a570-ffffffff8149a5c5: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814b4770)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff814b4770-ffffffff814b47c5: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81513d00)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:ima_file_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81513d00-ffffffff81513d58: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81530e50)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81530e50-ffffffff81530ea8: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81539280)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81539280-ffffffff815392d8: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81597ac0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_protect_xattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81597ac0-ffffffff81597b18: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8163c250)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_protect_xattr
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8163c250-ffffffff8163c2b6: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff816f3a50)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff816f3a50-ffffffff816f3ab6: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8172db70)
Location: security/integrity/iint.c:55
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8172db70-ffffffff8172dbd6: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8176e4b0)
Location: security/integrity/iint.c:55
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8176e4b0-ffffffff8176e516: integrity_iint_find (STB_GLOBAL)
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
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffff8000105ac678)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffff8000105ac678-ffff8000105ac75c: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (c075c0d0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
c075c0d0-c075c168: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (c00000000072ab80)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
c00000000072ab80-c00000000072ac38: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffe0003f4f3a)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffe0003f4f3a-ffffffe0003f4fa2: integrity_iint_find (STB_GLOBAL)
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
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814acd50)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff814acd50-ffffffff814acda5: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8149d770)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8149d770-ffffffff8149d7c5: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814a8df0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff814a8df0-ffffffff814a8e45: integrity_iint_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct integrity_iint_cache *integrity_iint_find(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814c17e0)
Location: security/integrity/iint.c:57
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff814c17e0-ffffffff814c183e: integrity_iint_find (STB_GLOBAL)
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
