# Function: <code>leftmatch_fb</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81436b0d)
Location: security/apparmor/match.c:651
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff8145376d)
Location: security/apparmor/match.c:651
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff814810e1)
Location: security/apparmor/match.c:647
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff8149ade4)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f33e0)
Location: security/apparmor/match.c:703
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff814f33e0-ffffffff814f35b9: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815105b0)
Location: security/apparmor/match.c:703
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff815105b0-ffffffff81510789: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81516f60)
Location: security/apparmor/match.c:703
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff81516f60-ffffffff8151713d: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81574f60)
Location: security/apparmor/match.c:703
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff81574f60-ffffffff8157513d: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81612970)
Location: security/apparmor/match.c:701
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff81612970-ffffffff81612b53: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c5540)
Location: security/apparmor/match.c:701
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff816c5540-ffffffff816c5723: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fe140)
Location: security/apparmor/match.c:657
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff816fe140-ffffffff816fe50b: leftmatch_fb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa *dfa, unsigned int start, const char *str, struct match_workbuf *wb, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173b6d0)
Location: security/apparmor/match.c:657
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
```
**Symbols:**

```
ffffffff8173b6d0-ffffffff8173ba9b: leftmatch_fb (STB_LOCAL)
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
In security/apparmor/match.c (ffff800010591014)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (c0741ccc)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (c0000000007049cc)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffe0003dea8e)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff814933c4)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff81483de4)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff8148f464)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
In security/apparmor/match.c (ffffffff814a7374)
Location: security/apparmor/match.c:662
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
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
