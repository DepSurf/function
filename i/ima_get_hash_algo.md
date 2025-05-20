# Function: <code>ima_get_hash_algo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8139a400)
Location: security/integrity/ima/ima_appraise.c:133
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff8139a400-ffffffff8139a4a3: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff813d7240)
Location: security/integrity/ima/ima_appraise.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813d7240-ffffffff813d72e4: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff813eeee0)
Location: security/integrity/ima/ima_appraise.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813eeee0-ffffffff813eef84: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff813fb450)
Location: security/integrity/ima/ima_appraise.c:141
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813fb450-ffffffff813fb4e4: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814238f0)
Location: security/integrity/ima/ima_appraise.c:141
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814238f0-ffffffff81423984: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81455f90)
Location: security/integrity/ima/ima_appraise.c:152
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81455f90-ffffffff81456024: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814733a0)
Location: security/integrity/ima/ima_appraise.c:152
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814733a0-ffffffff81473434: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814a10a0)
Location: security/integrity/ima/ima_appraise.c:150
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814a10a0-ffffffff814a1134: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814bb860)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814bb860-ffffffff814bb8f4: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8151be90)
Location: security/integrity/ima/ima_appraise.c:157
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8151be90-ffffffff8151bf23: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81538d00)
Location: security/integrity/ima/ima_appraise.c:173
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81538d00-ffffffff81538d93: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81541430)
Location: security/integrity/ima/ima_appraise.c:175
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81541430-ffffffff8154149b: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum hash_algo ima_get_hash_algo(const struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff815a11c0)
Location: security/integrity/ima/ima_appraise.c:175
Inline: True
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
**Symbols:**

```
ffffffff815a11c0-ffffffff815a122f: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(const struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81647490)
Location: security/integrity/ima/ima_appraise.c:178
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
**Symbols:**

```
ffffffff81647490-ffffffff8164751a: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(const struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff816ffc90)
Location: security/integrity/ima/ima_appraise.c:178
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
**Symbols:**

```
ffffffff816ffc90-ffffffff816ffd1a: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(const struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81739d10)
Location: security/integrity/ima/ima_appraise.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
**Symbols:**

```
ffffffff81739d10-ffffffff81739d9a: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(const struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8177a820)
Location: security/integrity/ima/ima_appraise.c:180
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
**Symbols:**

```
ffffffff8177a820-ffffffff8177a8aa: ima_get_hash_algo (STB_GLOBAL)
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
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffff8000105b40e8)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffff8000105b40e8-ffff8000105b41c0: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (c0763390)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
c0763390-c07634c0: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (c0000000007369a0)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
c0000000007369a0-c000000000736ab0: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffe0003fb444)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffe0003fb444-ffffffe0003fb4fa: ima_get_hash_algo (STB_GLOBAL)
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
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814b3e40)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814b3e40-ffffffff814b3ed4: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814a4860)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814a4860-ffffffff814a48f4: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814afed0)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814afed0-ffffffff814aff64: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum hash_algo ima_get_hash_algo(struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814c8950)
Location: security/integrity/ima/ima_appraise.c:151
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814c8950-ffffffff814c89e4: ima_get_hash_algo (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ima_digest_data *hash</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>enum hash_algo</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct evm_ima_xattr_data *xattr_value</code> ➡️ <code>const struct evm_ima_xattr_data *xattr_value</code>
</li>
</ul>
</details>
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
