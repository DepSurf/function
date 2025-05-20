# Function: <code>tpm_transmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, const char *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523990)
Location: drivers/char/tpm/tpm-interface.c:333
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
```
**Symbols:**

```
ffffffff81523990-ffffffff81523b98: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, const char *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815768b0)
Location: drivers/char/tpm/tpm-interface.c:333
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
```
**Symbols:**

```
ffffffff815768b0-ffffffff81576ac5: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, const u8 *buf, size_t bufsiz, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a2f20)
Location: drivers/char/tpm/tpm-interface.c:334
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-dev.c:tpm_write
```
**Symbols:**

```
ffffffff815a2f20-ffffffff815a318d: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, struct tpm_space *space, u8 *buf, size_t bufsiz, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6a80)
Location: drivers/char/tpm/tpm-interface.c:384
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
```
**Symbols:**

```
ffffffff815b6a80-ffffffff815b6ede: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, struct tpm_space *space, u8 *buf, size_t bufsiz, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d7b0)
Location: drivers/char/tpm/tpm-interface.c:384
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
```
**Symbols:**

```
ffffffff8161d7b0-ffffffff8161dc7e: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, struct tpm_space *space, u8 *buf, size_t bufsiz, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816571e0)
Location: drivers/char/tpm/tpm-interface.c:587
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
```
**Symbols:**

```
ffffffff816571e0-ffffffff8165798c: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, struct tpm_space *space, u8 *buf, size_t bufsiz, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676530)
Location: drivers/char/tpm/tpm-interface.c:328
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_async_work
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81676530-ffffffff81676cd7: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff816ac8af-ffffffff816ac987: tpm_transmit.cold (STB_LOCAL)
ffffffff816ac310-ffffffff816ac6e9: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff816cf58f-ffffffff816cf667: tpm_transmit.cold (STB_LOCAL)
ffffffff816cf070-ffffffff816cf449: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff817844b1-ffffffff817844ed: tpm_transmit.cold (STB_LOCAL)
ffffffff81784090-ffffffff817842d2: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81c0a40e-ffffffff81c0a44a: tpm_transmit.cold (STB_LOCAL)
ffffffff8179b5e0-ffffffff8179b822: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81bfbea1-ffffffff81bfbedd: tpm_transmit.cold (STB_LOCAL)
ffffffff8177e120-ffffffff8177e35f: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81cfcb5b-ffffffff81cfcb97: tpm_transmit.cold (STB_LOCAL)
ffffffff81804310-ffffffff81804558: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81ec5340-ffffffff81ec537e: tpm_transmit.cold (STB_LOCAL)
ffffffff81943c80-ffffffff81943eea: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa68a0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81aa68a0-ffffffff81aa6b55: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af20f0)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81af20f0-ffffffff81af2394: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45680)
Location: drivers/char/tpm/tpm-interface.c:153
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81b45680-ffffffff81b45924: tpm_transmit (STB_GLOBAL)
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
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b96a8)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffff8000108b96a8-ffff8000108b99e4: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2acc)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
c09b2acc-c09b2e20: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a5f0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
c00000000095a5f0-c00000000095aa50: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569a6a)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffe000569a6a-ffffffe000569e50: tpm_transmit (STB_GLOBAL)
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
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff81694fdf-ffffffff816950b7: tpm_transmit.cold (STB_LOCAL)
ffffffff81694ac0-ffffffff81694e99: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff816729cf-ffffffff81672aa7: tpm_transmit.cold (STB_LOCAL)
ffffffff816724b0-ffffffff81672889: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff816c324f-ffffffff816c3327: tpm_transmit.cold (STB_LOCAL)
ffffffff816c2d30-ffffffff816c3109: tpm_transmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit(struct tpm_chip *chip, u8 *buf, size_t bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:152
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
```
**Symbols:**

```
ffffffff816dd81f-ffffffff816dd8f7: tpm_transmit.cold (STB_LOCAL)
ffffffff816dd300-ffffffff816dd6d9: tpm_transmit (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *buf</code> ➡️ <code>const u8 *buf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_space *space</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, buf, bufsiz, flags</code> ➡️ <code>chip, space, buf, bufsiz, flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>const u8 *buf</code> ➡️ <code>u8 *buf</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tpm_space *space</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, buf, bufsiz, flags</code> ➡️ <code>chip, buf, bufsiz</code>
</li>
</ul>
</details>
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
