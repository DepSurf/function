# Function: <code>datablob_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81336d80)
Location: security/keys/trusted.c:856
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81338920)
Location: security/keys/encrypted-keys/encrypted.c:177
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81336d80-ffffffff81336eda: datablob_parse (STB_LOCAL)
ffffffff81338920-ffffffff81338b94: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8136c300)
Location: security/keys/trusted.c:856
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136df30)
Location: security/keys/encrypted-keys/encrypted.c:177
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8136c300-ffffffff8136c45c: datablob_parse (STB_LOCAL)
ffffffff8136df30-ffffffff8136e1a9: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81382b20)
Location: security/keys/trusted.c:856
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384750)
Location: security/keys/encrypted-keys/encrypted.c:177
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81382b20-ffffffff81382c7c: datablob_parse (STB_LOCAL)
ffffffff81384750-ffffffff813849c9: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813971c0)
Location: security/keys/trusted.c:856
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81398d70)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813971c0-ffffffff8139732c: datablob_parse (STB_LOCAL)
ffffffff81398d70-ffffffff81398fea: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813bc9a0)
Location: security/keys/trusted.c:856
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813be580)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813bc9a0-ffffffff813bcb0c: datablob_parse (STB_LOCAL)
ffffffff813be580-ffffffff813be7fa: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff813ed7c0)
Location: security/keys/trusted.c:855
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813ed7c0-ffffffff813ed91c: datablob_parse (STB_LOCAL)
ffffffff813ef490-ffffffff813ef658: datablob_parse (STB_LOCAL)
ffffffff813f0a5a-ffffffff813f0b2c: datablob_parse.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81409020)
Location: security/keys/trusted.c:859
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:174
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81409020-ffffffff81409163: datablob_parse (STB_LOCAL)
ffffffff8140a6e0-ffffffff8140a8a8: datablob_parse (STB_LOCAL)
ffffffff8140bd3a-ffffffff8140be0c: datablob_parse.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81435b80)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81435b80-ffffffff81435cc1: datablob_parse (STB_LOCAL)
ffffffff814378f0-ffffffff81437ab6: datablob_parse (STB_LOCAL)
ffffffff81438e6d-ffffffff81438f58: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff8144f920)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8144f920-ffffffff8144fa61: datablob_parse (STB_LOCAL)
ffffffff81451620-ffffffff814517e6: datablob_parse (STB_LOCAL)
ffffffff81452cbf-ffffffff81452daa: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a10c0)
Location: security/keys/trusted-keys/trusted_tpm1.c:850
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814a10c0-ffffffff814a11ff: datablob_parse (STB_LOCAL)
ffffffff814a4590-ffffffff814a4771: datablob_parse (STB_LOCAL)
ffffffff814a568d-ffffffff814a5778: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bea80)
Location: security/keys/trusted-keys/trusted_tpm1.c:860
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814bea80-ffffffff814bebbf: datablob_parse (STB_LOCAL)
ffffffff814c1d90-ffffffff814c1f71: datablob_parse (STB_LOCAL)
ffffffff81beff20-ffffffff81bf000b: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char **datablob, struct trusted_key_payload *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_core.c (ffffffff814c4540)
Location: security/keys/trusted-keys/trusted_core.c:65
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/trusted-keys/trusted_core.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff814c4540-ffffffff814c4660: datablob_parse (STB_LOCAL)
ffffffff814c8200-ffffffff814c83f3: datablob_parse (STB_LOCAL)
ffffffff81be1f52-ffffffff81be203d: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char **datablob, struct trusted_key_payload *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_core.c (ffffffff8151cf20)
Location: security/keys/trusted-keys/trusted_core.c:65
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/trusted-keys/trusted_core.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8151cf20-ffffffff8151d040: datablob_parse (STB_LOCAL)
ffffffff81520cf0-ffffffff81520ee3: datablob_parse (STB_LOCAL)
ffffffff81cd31c3-ffffffff81cd32ae: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char **datablob, struct trusted_key_payload *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_core.c (ffffffff815b01f0)
Location: security/keys/trusted-keys/trusted_core.c:74
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/trusted-keys/trusted_core.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:176
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff815b01f0-ffffffff815b0335: datablob_parse (STB_LOCAL)
ffffffff815b44a0-ffffffff815b46f1: datablob_parse (STB_LOCAL)
ffffffff81e863be-ffffffff81e86477: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int datablob_parse(char **datablob, struct trusted_key_payload *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_core.c (ffffffff8165aab0)
Location: security/keys/trusted-keys/trusted_core.c:74
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/trusted-keys/trusted_core.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165f5d0)
Location: security/keys/encrypted-keys/encrypted.c:176
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8165aab0-ffffffff8165abf5: datablob_parse (STB_LOCAL)
ffffffff8165f5d0-ffffffff8165f8b5: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int datablob_parse(char **datablob, struct trusted_key_payload *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_core.c (ffffffff816933b0)
Location: security/keys/trusted-keys/trusted_core.c:74
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/trusted-keys/trusted_core.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697f50)
Location: security/keys/encrypted-keys/encrypted.c:176
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff816933b0-ffffffff816934f5: datablob_parse (STB_LOCAL)
ffffffff81697f50-ffffffff81698225: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int datablob_parse(char **datablob, struct trusted_key_payload *p);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_core.c (ffffffff816cf980)
Location: security/keys/trusted-keys/trusted_core.c:73
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/trusted-keys/trusted_core.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4380)
Location: security/keys/encrypted-keys/encrypted.c:176
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff816cf980-ffffffff816cfac5: datablob_parse (STB_LOCAL)
ffffffff816d4380-ffffffff816d4655: datablob_parse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053af78)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053c5d8)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffff80001053af78-ffff80001053b0c0: datablob_parse (STB_LOCAL)
ffff80001053c5d8-ffff80001053c82c: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f0b04)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2858)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
c06f0b04-c06f0c4c: datablob_parse (STB_LOCAL)
c06f2858-c06f2ac4: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c0000000006897e0)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068bd80)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
c0000000006897e0-c00000000068998c: datablob_parse (STB_LOCAL)
c00000000068bd80-c00000000068c08c: datablob_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe000398e3c)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a296)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffe000398e3c-ffffffe000398f68: datablob_parse (STB_LOCAL)
ffffffe00039a296-ffffffe00039a4aa: datablob_parse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81447f00)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81447f00-ffffffff81448041: datablob_parse (STB_LOCAL)
ffffffff81449c00-ffffffff81449dc6: datablob_parse (STB_LOCAL)
ffffffff8144b29f-ffffffff8144b38a: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81438950)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81438950-ffffffff81438a91: datablob_parse (STB_LOCAL)
ffffffff8143a650-ffffffff8143a816: datablob_parse (STB_LOCAL)
ffffffff8143bcef-ffffffff8143bdda: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81443fa0)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff81443fa0-ffffffff814440e1: datablob_parse (STB_LOCAL)
ffffffff81445ca0-ffffffff81445e66: datablob_parse (STB_LOCAL)
ffffffff8144733f-ffffffff8144742a: datablob_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int datablob_parse(char *datablob, struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff8145b2d0)
Location: security/keys/trusted.c:864
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:171
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff8145b2d0-ffffffff8145b411: datablob_parse (STB_LOCAL)
ffffffff8145cfd0-ffffffff8145d196: datablob_parse (STB_LOCAL)
ffffffff8145e66f-ffffffff8145e75a: datablob_parse.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct trusted_key_options *o</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *datablob</code> ➡️ <code>char **datablob</code>
</li>
</ul>
</details>
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
