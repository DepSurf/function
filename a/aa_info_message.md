# Function: <code>aa_info_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81378530)
Location: security/apparmor/lib.c:126
Inline: False
```
**Symbols:**

```
ffffffff81378530-ffffffff813785d1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813b1290)
Location: security/apparmor/lib.c:126
Inline: False
```
**Symbols:**

```
ffffffff813b1290-ffffffff813b1331: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813c8450)
Location: security/apparmor/lib.c:126
Inline: False
```
**Symbols:**

```
ffffffff813c8450-ffffffff813c84f1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813ddc50)
Location: security/apparmor/lib.c:126
Inline: False
```
**Symbols:**

```
ffffffff813ddc50-ffffffff813ddcf1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814045f0)
Location: security/apparmor/lib.c:126
Inline: False
```
**Symbols:**

```
ffffffff814045f0-ffffffff81404691: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:126
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff8143601c-ffffffff81436046: aa_info_message.cold.2 (STB_LOCAL)
ffffffff814356d0-ffffffff81435750: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:128
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff81452c3c-ffffffff81452c66: aa_info_message.cold.2 (STB_LOCAL)
ffffffff814522c0-ffffffff81452340: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff814805ea-ffffffff81480615: aa_info_message.cold (STB_LOCAL)
ffffffff8147fc70-ffffffff8147fcf1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff8149a2ea-ffffffff8149a315: aa_info_message.cold (STB_LOCAL)
ffffffff81499970-ffffffff814999f1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff814f2a6f-ffffffff814f2a98: aa_info_message.cold (STB_LOCAL)
ffffffff814f2060-ffffffff814f20e1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff81bf1652-ffffffff81bf167b: aa_info_message.cold (STB_LOCAL)
ffffffff8150f260-ffffffff8150f2e1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff81be3662-ffffffff81be368b: aa_info_message.cold (STB_LOCAL)
ffffffff81515c50-ffffffff81515cd1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff81cd628b-ffffffff81cd62b4: aa_info_message.cold (STB_LOCAL)
ffffffff81573c50-ffffffff81573cd1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:143
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff81e890bc-ffffffff81e890f3: aa_info_message.cold (STB_LOCAL)
ffffffff81611540-ffffffff816115c6: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c41c0)
Location: security/apparmor/lib.c:235
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff816c41c0-ffffffff816c4254: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fcd90)
Location: security/apparmor/lib.c:235
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff816fcd90-ffffffff816fce24: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a2f0)
Location: security/apparmor/lib.c:237
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff8173a2f0-ffffffff8173a384: aa_info_message (STB_GLOBAL)
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
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffff80001058f748)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffff80001058f748-ffff80001058f7ec: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c0740534)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
c0740534-c07405f0: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c000000000702a50)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
c000000000702a50-c000000000702b24: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffe0003dd3f8)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffe0003dd3f8-ffffffe0003dd48a: aa_info_message (STB_GLOBAL)
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
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff814928ca-ffffffff814928f5: aa_info_message.cold (STB_LOCAL)
ffffffff81491f50-ffffffff81491fd1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff814832ea-ffffffff81483315: aa_info_message.cold (STB_LOCAL)
ffffffff81482970-ffffffff814829f1: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff8148e96a-ffffffff8148e995: aa_info_message.cold (STB_LOCAL)
ffffffff8148dff0-ffffffff8148e071: aa_info_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void aa_info_message(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lib.c (0)
Location: security/apparmor/lib.c:124
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/crypto.c:init_profile_hash
```
**Symbols:**

```
ffffffff814a687a-ffffffff814a68a5: aa_info_message.cold (STB_LOCAL)
ffffffff814a5f00-ffffffff814a5f81: aa_info_message (STB_GLOBAL)
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
