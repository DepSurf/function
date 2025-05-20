# Function: <code>tpm2_auto_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8157a330)
Location: drivers/char/tpm/tpm2-cmd.c:951
Inline: False
```
**Symbols:**

```
ffffffff8157a330-ffffffff8157a3a0: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a6790)
Location: drivers/char/tpm/tpm2-cmd.c:962
Inline: False
```
**Symbols:**

```
ffffffff815a6790-ffffffff815a6800: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815bab90)
Location: drivers/char/tpm/tpm2-cmd.c:1079
Inline: False
```
**Symbols:**

```
ffffffff815bab90-ffffffff815bb118: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81621260)
Location: drivers/char/tpm/tpm2-cmd.c:1054
Inline: False
```
**Symbols:**

```
ffffffff81621260-ffffffff81621672: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b020)
Location: drivers/char/tpm/tpm2-cmd.c:1036
Inline: False
```
**Symbols:**

```
ffffffff8165b020-ffffffff8165b420: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81678fa0)
Location: drivers/char/tpm/tpm2-cmd.c:986
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81678fa0-ffffffff81679458: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:1021
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816afa4c-ffffffff816afb3d: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff816af6f0-ffffffff816af9eb: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816d274c-ffffffff816d283d: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff816d23e0-ffffffff816d26e4: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff8178699c-ffffffff81786a42: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff81786870-ffffffff81786937: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81c0a6a5-ffffffff81c0a74b: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff8179da70-ffffffff8179db37: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:723
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81bfc138-ffffffff81bfc203: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff81780590-ffffffff81780657: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:723
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81cfce61-ffffffff81cfcf07: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff818069a0-ffffffff81806a67: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:732
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81ec56b3-ffffffff81ec57c9: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff819464f0-ffffffff819465f4: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa95c0)
Location: drivers/char/tpm/tpm2-cmd.c:732
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81aa95c0-ffffffff81aa97d3: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4df0)
Location: drivers/char/tpm/tpm2-cmd.c:732
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81af4df0-ffffffff81af5000: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b483b0)
Location: drivers/char/tpm/tpm2-cmd.c:732
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81b483b0-ffffffff81b485c0: tpm2_auto_startup (STB_GLOBAL)
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
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bce90)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffff8000108bce90-ffff8000108bd2b0: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b628c)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
c09b628c-c09b66d8: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095eb90)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
c00000000095eb90-c00000000095f078: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056efb8)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffe00056efb8-ffffffe00056f634: tpm2_auto_startup (STB_GLOBAL)
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
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff8169819c-ffffffff8169828d: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff81697e30-ffffffff81698134: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81675b8c-ffffffff81675c7d: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff81675820-ffffffff81675b24: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816c640c-ffffffff816c64fd: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff816c60a0-ffffffff816c63a4: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm2_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:1027
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816e08fc-ffffffff816e09e2: tpm2_auto_startup.cold (STB_LOCAL)
ffffffff816e05a0-ffffffff816e0899: tpm2_auto_startup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
