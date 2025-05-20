# Function: <code>tpm2_save_context</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bbf70)
Location: drivers/char/tpm/tpm2-space.c:121
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff815bbf70-ffffffff815bc159: tpm2_save_context.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff816224c0)
Location: drivers/char/tpm/tpm2-space.c:121
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff816224c0-ffffffff81622636: tpm2_save_context.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c290)
Location: drivers/char/tpm/tpm2-space.c:123
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff8165c290-ffffffff8165c406: tpm2_save_context.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81679600)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81679600-ffffffff81679776: tpm2_save_context.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff816afc10-ffffffff816afd8a: tpm2_save_context.constprop.0 (STB_LOCAL)
ffffffff816b0834-ffffffff816b08bc: tpm2_save_context.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff816d2910-ffffffff816d2a8a: tpm2_save_context.constprop.0 (STB_LOCAL)
ffffffff816d3534-ffffffff816d35bc: tpm2_save_context.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
```
**Symbols:**

```
ffffffff81786e20-ffffffff81786f8a: tpm2_save_context (STB_LOCAL)
ffffffff81787780-ffffffff81787808: tpm2_save_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
```
**Symbols:**

```
ffffffff8179df30-ffffffff8179e09a: tpm2_save_context (STB_LOCAL)
ffffffff81c0a7c7-ffffffff81c0a84f: tpm2_save_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff817808f0-ffffffff81780a58: tpm2_save_context (STB_LOCAL)
ffffffff81bfc25f-ffffffff81bfc2e8: tpm2_save_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81806d00-ffffffff81806e68: tpm2_save_context (STB_LOCAL)
ffffffff81cfcf63-ffffffff81cfcfec: tpm2_save_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81946900-ffffffff81946a81: tpm2_save_context (STB_LOCAL)
ffffffff81ec5809-ffffffff81ec586a: tpm2_save_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81aa9b80)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81aa9b80-ffffffff81aa9d60: tpm2_save_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81af51c0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81af51c0-ffffffff81af53a0: tpm2_save_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_save_context(struct tpm_chip *chip, u32 handle, u8 *buf, unsigned int buf_size, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81b487b0)
Location: drivers/char/tpm/tpm2-space.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81b487b0-ffffffff81b48990: tpm2_save_context (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd410)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffff8000108bd410-ffff8000108bd634: tpm2_save_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c09b67f8)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
c09b67f8-c09b6a60: tpm2_save_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c00000000095f230)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
c00000000095f230-c00000000095f4e4: tpm2_save_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffe00056f776)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffe00056f776-ffffffe00056fa4c: tpm2_save_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81698360-ffffffff816984da: tpm2_save_context.constprop.0 (STB_LOCAL)
ffffffff81698f84-ffffffff8169900c: tpm2_save_context.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81675d50-ffffffff81675eca: tpm2_save_context.constprop.0 (STB_LOCAL)
ffffffff81676974-ffffffff816769fc: tpm2_save_context.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff816c65d0-ffffffff816c674a: tpm2_save_context.constprop.0 (STB_LOCAL)
ffffffff816c71f4-ffffffff816c727c: tpm2_save_context.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:119
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff816e0ac0-ffffffff816e0c35: tpm2_save_context.constprop.0 (STB_LOCAL)
ffffffff816e16e4-ffffffff816e176c: tpm2_save_context.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
