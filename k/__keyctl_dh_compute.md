# Function: <code>__keyctl_dh_compute</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81395ca0)
Location: security/keys/dh.c:239
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81395ca0-ffffffff813965a2: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813bb420)
Location: security/keys/dh.c:239
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff813bb420-ffffffff813bbd33: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:232
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff813ecb1f-ffffffff813ecb47: __keyctl_dh_compute.cold.3 (STB_LOCAL)
ffffffff813ec250-ffffffff813eca96: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:232
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff814076ff-ffffffff81407735: __keyctl_dh_compute.cold.4 (STB_LOCAL)
ffffffff81406e50-ffffffff8140767b: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff814348ca-ffffffff81434900: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff81433ff0-ffffffff81434836: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff8144e64a-ffffffff8144e680: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff8144dd40-ffffffff8144e5be: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814a0070)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff814a0070-ffffffff814a05e7: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814bda80)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff814bda80-ffffffff814bdff7: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814c38f0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff814c38f0-ffffffff814c3e61: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8151c2c0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff8151c2c0-ffffffff8151c831: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:138
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81e86082-ffffffff81e860b8: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff815af2e0-ffffffff815af9c9: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81659af0)
Location: security/keys/dh.c:138
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81659af0-ffffffff8165a1c1: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81692350)
Location: security/keys/dh.c:122
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81692350-ffffffff81692a94: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff816ce920)
Location: security/keys/dh.c:122
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff816ce920-ffffffff816cf064: __keyctl_dh_compute (STB_GLOBAL)
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
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffff8000105385e0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffff8000105385e0-ffff800010538af4: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (c06eef60)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
c06eef60-c06ef5b4: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (c0000000006870b0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
c0000000006870b0-c000000000687a10: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffe0003972f2)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffe0003972f2-ffffffe000397784: __keyctl_dh_compute (STB_GLOBAL)
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
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81446c2a-ffffffff81446c60: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff81446320-ffffffff81446b9e: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff8143767a-ffffffff814376b0: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff81436d70-ffffffff814375ee: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81442cca-ffffffff81442d00: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff814423c0-ffffffff81442c3e: __keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdfcopy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/dh.c (0)
Location: security/keys/dh.c:227
Inline: False
Direct callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
```
**Symbols:**

```
ffffffff81459ffa-ffffffff8145a030: __keyctl_dh_compute.cold (STB_LOCAL)
ffffffff814596f0-ffffffff81459f6e: __keyctl_dh_compute (STB_GLOBAL)
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
