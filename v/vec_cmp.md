# Function: <code>vec_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389060)
Location: security/apparmor/label.c:167
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81389060-ffffffff813891d3: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c3c00)
Location: security/apparmor/label.c:167
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813c3c00-ffffffff813c3d97: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813db190)
Location: security/apparmor/label.c:167
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813db190-ffffffff813db327: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ec8f0)
Location: security/apparmor/label.c:169
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813ec8f0-ffffffff813ec95c: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414280)
Location: security/apparmor/label.c:169
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81414280-ffffffff814142ec: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446600)
Location: security/apparmor/label.c:169
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81446600-ffffffff81446677: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463520)
Location: security/apparmor/label.c:169
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81463520-ffffffff81463597: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814907f0)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814907f0-ffffffff81490867: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aa6b0)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814aa6b0-ffffffff814aa727: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81508499)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81525459)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152b549)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815898e9)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162a1c1)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816de9c1)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81717fc1)
Location: security/apparmor/label.c:165
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81756a31)
Location: security/apparmor/label.c:166
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
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
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1438)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffff8000105a1438-ffff8000105a14c4: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0751d00)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
c0751d00-c0751d64: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071bee0)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
c00000000071bee0-c00000000071bfd0: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec086)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffe0003ec086-ffffffe0003ec110: vec_cmp (STB_LOCAL)
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
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a2c90)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814a2c90-ffffffff814a2d07: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814936b0)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814936b0-ffffffff81493727: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149ed30)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff8149ed30-ffffffff8149eda7: vec_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vec_cmp(struct aa_profile **a, int an, struct aa_profile **b, int bn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7360)
Location: security/apparmor/label.c:165
Inline: False
Direct callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814b7360-ffffffff814b73d7: vec_cmp (STB_LOCAL)
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
