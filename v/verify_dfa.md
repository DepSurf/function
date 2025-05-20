# Function: <code>verify_dfa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813792b5)
Location: security/apparmor/match.c:127
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b1e6c)
Location: security/apparmor/match.c:131
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c902c)
Location: security/apparmor/match.c:131
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813de988)
Location: security/apparmor/match.c:131
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8140531e)
Location: security/apparmor/match.c:131
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814364b3)
Location: security/apparmor/match.c:198
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81453105)
Location: security/apparmor/match.c:198
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81480a86)
Location: security/apparmor/match.c:194
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149a76f)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:197
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff814f2bf0-ffffffff814f2d35: verify_dfa (STB_LOCAL)
ffffffff814f3950-ffffffff814f39be: verify_dfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:197
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff8150fdc0-ffffffff8150ff05: verify_dfa (STB_LOCAL)
ffffffff81bf167b-ffffffff81bf16e9: verify_dfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:197
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81516650-ffffffff81516798: verify_dfa (STB_LOCAL)
ffffffff81be368b-ffffffff81be36f9: verify_dfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:197
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81574650-ffffffff81574798: verify_dfa (STB_LOCAL)
ffffffff81cd62b4-ffffffff81cd6322: verify_dfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:197
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff816120f0-ffffffff81612246: verify_dfa (STB_LOCAL)
ffffffff81e890f3-ffffffff81e89141: verify_dfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c4e20)
Location: security/apparmor/match.c:197
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff816c4e20-ffffffff816c4fdc: verify_dfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fd840)
Location: security/apparmor/match.c:153
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff816fd840-ffffffff816fd9eb: verify_dfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_dfa(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173ada0)
Location: security/apparmor/match.c:153
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff8173ada0-ffffffff8173af4b: verify_dfa (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590850)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0741594)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c000000000704028)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003de2f2)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81492d4f)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148376f)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148edef)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a6cff)
Location: security/apparmor/match.c:197
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
