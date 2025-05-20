# Function: <code>aa_audit_perm_names</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const char **names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813786b0)
Location: security/apparmor/lib.c:241
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff813786b0-ffffffff81378739: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const char **names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813b1410)
Location: security/apparmor/lib.c:241
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff813b1410-ffffffff813b1499: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const char **names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813c85d0)
Location: security/apparmor/lib.c:241
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff813c85d0-ffffffff813c8659: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813ddd80)
Location: security/apparmor/lib.c:214
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff813ddd80-ffffffff813dde09: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81404720)
Location: security/apparmor/lib.c:214
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff81404720-ffffffff814047a9: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814357d0)
Location: security/apparmor/lib.c:214
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff814357d0-ffffffff81435859: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81452400)
Location: security/apparmor/lib.c:225
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff81452400-ffffffff81452489: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8147fdc0)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff8147fdc0-ffffffff8147fe46: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81499ac0)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff81499ac0-ffffffff81499b46: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814f2321)
Location: security/apparmor/lib.c:221
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff814f21b0-ffffffff814f2236: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8150f521)
Location: security/apparmor/lib.c:221
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff8150f3b0-ffffffff8150f436: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81515f0e)
Location: security/apparmor/lib.c:221
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff81515da0-ffffffff81515e26: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81573f0e)
Location: security/apparmor/lib.c:221
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff81573da0-ffffffff81573e26: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81611889)
Location: security/apparmor/lib.c:240
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff816116d0-ffffffff81611763: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c4569)
Location: security/apparmor/lib.c:332
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff816c43a0-ffffffff816c4433: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fd139)
Location: security/apparmor/lib.c:332
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff816fcf70-ffffffff816fd003: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a699)
Location: security/apparmor/lib.c:334
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff8173a4d0-ffffffff8173a563: aa_audit_perm_names (STB_GLOBAL)
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
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffff80001058f910)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffff80001058f910-ffff80001058f9b8: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c07406ec)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
c07406ec-c074077c: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c000000000702cc0)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
c000000000702cc0-c000000000702dac: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffe0003dd56c)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffe0003dd56c-ffffffe0003dd5f8: aa_audit_perm_names (STB_GLOBAL)
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
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814920a0)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff814920a0-ffffffff81492126: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81482ac0)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff81482ac0-ffffffff81482b46: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8148e140)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff8148e140-ffffffff8148e1c6: aa_audit_perm_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_audit_perm_names(struct audit_buffer *ab, const const char * *names, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814a6050)
Location: security/apparmor/lib.c:221
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
```
**Symbols:**

```
ffffffff814a6050-ffffffff814a60d6: aa_audit_perm_names (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char **names</code> ➡️ <code>const const char * *names</code>
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
