# Function: <code>wait_for_random_bytes</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a5c60)
Location: drivers/char/random.c:1549
Inline: True
Direct callers:
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff815a5c60-ffffffff815a5cfe: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160c560)
Location: drivers/char/random.c:1548
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff8160c560-ffffffff8160c5fe: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81645e60)
Location: drivers/char/random.c:1653
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff81645e60-ffffffff81645efb: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81664160)
Location: drivers/char/random.c:1662
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff81664160-ffffffff816641fb: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81699a60)
Location: drivers/char/random.c:1744
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff81699a60-ffffffff81699af2: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bc670)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff816bc670-ffffffff816bc82b: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81773075)
Location: drivers/char/random.c:1640
Inline: True
Inline callers:
  - drivers/char/random.c:random_read
Direct callers:
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read
```
**Symbols:**

```
ffffffff81771230-ffffffff8177133c: wait_for_random_bytes.part.0 (STB_LOCAL)
ffffffff81771340-ffffffff8177135c: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8178e045)
Location: drivers/char/random.c:1639
Inline: True
Inline callers:
  - drivers/char/random.c:random_read
Direct callers:
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read
```
**Symbols:**

```
ffffffff8178c260-ffffffff8178c36c: wait_for_random_bytes.part.0 (STB_LOCAL)
ffffffff8178c370-ffffffff8178c38c: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81770a39)
Location: drivers/char/random.c:1615
Inline: True
Inline callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/random.c:random_read
Direct callers:
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/random.c:random_read
```
**Symbols:**

```
ffffffff8176eff0-ffffffff8176f1a4: wait_for_random_bytes.part.0 (STB_LOCAL)
ffffffff8176f1b0-ffffffff8176f1cc: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff817f63d5)
Location: drivers/char/random.c:1635
Inline: True
Inline callers:
  - drivers/char/random.c:random_read
Direct callers:
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read
```
**Symbols:**

```
ffffffff817f4830-ffffffff817f49e1: wait_for_random_bytes.part.0 (STB_LOCAL)
ffffffff817f49f0-ffffffff817f4a0c: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:129
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read_iter
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81ec2db5-ffffffff81ec2e76: wait_for_random_bytes.cold (STB_LOCAL)
ffffffff81934100-ffffffff8193415d: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a94f70)
Location: drivers/char/random.c:132
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read_iter
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81a94f70-ffffffff81a9508d: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81ae0790)
Location: drivers/char/random.c:132
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read_iter
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81ae0790-ffffffff81ae08ad: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b33b90)
Location: drivers/char/random.c:132
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - crypto/rng.c:crypto_rng_reset
  - drivers/char/random.c:random_read_iter
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81b33b90-ffffffff81b33cad: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108adf48)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffff8000108adf48-ffff8000108ae180: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a977c)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
c09a977c-c09a99d4: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000945f70)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
c000000000945f70-c000000000946224: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe00056179c)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffe00056179c-ffffffe00056191e: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816820d0)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff816820d0-ffffffff8168228b: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8165ff50)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff8165ff50-ffffffff8166010b: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b04b0)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff816b04b0-ffffffff816b066b: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int wait_for_random_bytes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cac00)
Location: drivers/char/random.c:1795
Inline: True
Direct callers:
  - security/keys/big_key.c:big_key_preparse
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff816cac00-ffffffff816cadad: wait_for_random_bytes (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
