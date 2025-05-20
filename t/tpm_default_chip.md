# Function: <code>tpm_default_chip</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81675220)
Location: drivers/char/tpm/tpm-chip.c:86
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81675220-ffffffff816752b6: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816aaea0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff816aaea0-ffffffff816aaf2c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816cdbe0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff816cdbe0-ffffffff816cdc6c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff817828e0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff817828e0-ffffffff8178296c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81799f30)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81799f30-ffffffff81799fbc: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8177cab0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff8177cab0-ffffffff8177cb3c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81802c80)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81802c80-ffffffff81802d0c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff819424b0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff819424b0-ffffffff81942547: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa4be0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81aa4be0-ffffffff81aa4c77: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0500)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81af0500-ffffffff81af0597: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81b43a40)
Location: drivers/char/tpm/tpm-chip.c:201
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81b43a40-ffffffff81b43ad7: tpm_default_chip (STB_GLOBAL)
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
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffff8000108b7d68)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffff8000108b7d68-ffff8000108b7e14: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c09b1634)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
c09b1634-c09b16dc: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c0000000009586b0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
c0000000009586b0-c00000000095878c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffe00056867a)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffe00056867a-ffffffe0005686f8: tpm_default_chip (STB_GLOBAL)
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
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81693630)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81693630-ffffffff816936bc: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81671020)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff81671020-ffffffff816710ac: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816c18a0)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff816c18a0-ffffffff816c192c: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tpm_chip *tpm_default_chip();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816dbe70)
Location: drivers/char/tpm/tpm-chip.c:196
Inline: False
Direct callers:
  - security/keys/trusted.c:init_trusted
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/char/tpm/tpm-chip.c:tpm_find_get_ops
```
**Symbols:**

```
ffffffff816dbe70-ffffffff816dbefc: tpm_default_chip (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
