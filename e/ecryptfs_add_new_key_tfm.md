# Function: <code>ecryptfs_add_new_key_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306ca0)
Location: fs/ecryptfs/crypto.c:1672
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81306ca0-ffffffff81306edf: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133aec0)
Location: fs/ecryptfs/crypto.c:1663
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff8133aec0-ffffffff8133b0f5: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350c50)
Location: fs/ecryptfs/crypto.c:1663
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81350c50-ffffffff81350e89: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365770)
Location: fs/ecryptfs/crypto.c:1663
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81365770-ffffffff813659bb: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138a430)
Location: fs/ecryptfs/crypto.c:1642
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff8138a430-ffffffff8138a672: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1642
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff813b9c1e-ffffffff813b9ccb: ecryptfs_add_new_key_tfm.cold.37 (STB_LOCAL)
ffffffff813b91c0-ffffffff813b9355: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1642
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff813d31cd-ffffffff813d327a: ecryptfs_add_new_key_tfm.cold.35 (STB_LOCAL)
ffffffff813d2730-ffffffff813d28c5: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1636
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff813fdcbc-ffffffff813fdd77: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff813fd1d0-ffffffff813fd36a: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81417ba8-ffffffff81417c63: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff814170b0-ffffffff8141724b: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1623
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff814661a2-ffffffff814661d7: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff814657e0-ffffffff814658c4: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1623
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81bee959-ffffffff81bee98e: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff81481080-ffffffff81481164: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1617
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81be09a4-ffffffff81be0a64: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff81486970-ffffffff81486b0c: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1617
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81cd1141-ffffffff81cd1201: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff814de100-ffffffff814de29c: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1617
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81e8433d-ffffffff81e843cb: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff8156c100-ffffffff8156c2d9: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81610290)
Location: fs/ecryptfs/crypto.c:1617
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81610290-ffffffff81610500: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81648120)
Location: fs/ecryptfs/crypto.c:1593
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81648120-ffffffff8164837d: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816815d0)
Location: fs/ecryptfs/crypto.c:1593
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff816815d0-ffffffff8168182d: ecryptfs_add_new_key_tfm (STB_GLOBAL)
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
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f8b08)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffff8000104f8b08-ffff8000104f8d48: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b63a8)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
c06b63a8-c06b65ec: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063a8d0)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
c00000000063a8d0-c00000000063abcc: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe0003673ee)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffe0003673ee-ffffffe0003675ee: ecryptfs_add_new_key_tfm (STB_GLOBAL)
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
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81410188-ffffffff81410243: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff8140f690-ffffffff8140f82b: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81400c08-ffffffff81400cc3: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff81400110-ffffffff814002ab: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff8140d508-ffffffff8140d5c3: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff8140ca10-ffffffff8140cbab: ecryptfs_add_new_key_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_add_new_key_tfm(struct ecryptfs_key_tfm **key_tfm, char *cipher_name, size_t key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1638
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_get_tfm_and_mutex_for_cipher_name
```
**Symbols:**

```
ffffffff81423181-ffffffff8142323c: ecryptfs_add_new_key_tfm.cold (STB_LOCAL)
ffffffff81422690-ffffffff8142282b: ecryptfs_add_new_key_tfm (STB_GLOBAL)
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
