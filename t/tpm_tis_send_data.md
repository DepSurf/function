# Function: <code>tpm_tis_send_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528c80)
Location: drivers/char/tpm/tpm_tis.c:305
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81528c80-ffffffff81528e97: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157bf50)
Location: drivers/char/tpm/tpm_tis_core.c:252
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8157bf50-ffffffff8157c1f5: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a83d0)
Location: drivers/char/tpm/tpm_tis_core.c:262
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815a83d0-ffffffff815a86ae: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bd8c0)
Location: drivers/char/tpm/tpm_tis_core.c:255
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815bd8c0-ffffffff815bdb5b: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623f20)
Location: drivers/char/tpm/tpm_tis_core.c:258
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81623f20-ffffffff816241e5: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165e150)
Location: drivers/char/tpm/tpm_tis_core.c:366
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8165e150-ffffffff8165e429: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c610)
Location: drivers/char/tpm/tpm_tis_core.c:366
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8167c610-ffffffff8167c8e9: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816b34c0-ffffffff816b376f: tpm_tis_send_data (STB_LOCAL)
ffffffff816b42b7-ffffffff816b42d2: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816d61a0-ffffffff816d644f: tpm_tis_send_data (STB_LOCAL)
ffffffff816d6f97-ffffffff816d6fb2: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8178ab50-ffffffff8178ae09: tpm_tis_send_data (STB_LOCAL)
ffffffff8178b574-ffffffff8178b58f: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:329
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff817a1870-ffffffff817a1ab6: tpm_tis_send_data (STB_LOCAL)
ffffffff81c0ac9a-ffffffff81c0acb5: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:340
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81784570-ffffffff817847b7: tpm_tis_send_data (STB_LOCAL)
ffffffff81bfc6ec-ffffffff81bfc707: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:341
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8180afc0-ffffffff8180b207: tpm_tis_send_data (STB_LOCAL)
ffffffff81cfd430-ffffffff81cfd44b: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:341
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8194b3a0-ffffffff8194b60c: tpm_tis_send_data (STB_LOCAL)
ffffffff81ec5cfa-ffffffff81ec5d15: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaee90)
Location: drivers/char/tpm/tpm_tis_core.c:349
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81aaee90-ffffffff81aaf11b: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afa480)
Location: drivers/char/tpm/tpm_tis_core.c:411
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81afa480-ffffffff81afa720: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4dae0)
Location: drivers/char/tpm/tpm_tis_core.c:432
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81b4dae0-ffffffff81b4ddbc: tpm_tis_send_data (STB_LOCAL)
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
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1508)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffff8000108c1508-ffff8000108c17e0: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b99a8)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
c09b99a8-c09b9c88: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c0000000009633b0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
c0000000009633b0-c0000000009637c0: tpm_tis_send_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe0005727d6)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffe0005727d6-ffffffe000572a08: tpm_tis_send_data (STB_LOCAL)
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
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8169bbf0-ffffffff8169be9f: tpm_tis_send_data (STB_LOCAL)
ffffffff8169c9e7-ffffffff8169ca02: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816795e0-ffffffff8167988f: tpm_tis_send_data (STB_LOCAL)
ffffffff8167a3d7-ffffffff8167a3f2: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816c9e60-ffffffff816ca10f: tpm_tis_send_data (STB_LOCAL)
ffffffff816cac57-ffffffff816cac72: tpm_tis_send_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm_tis_send_data(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816e4330-ffffffff816e45df: tpm_tis_send_data (STB_LOCAL)
ffffffff816e5127-ffffffff816e5142: tpm_tis_send_data.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 *buf</code> ➡️ <code>const u8 *buf</code>
</li>
</ul>
</details>
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
