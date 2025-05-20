# Function: <code>pwmchip_find_by_name</code>

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
In drivers/pwm/core.c (ffffffff8142caab)
Location: drivers/pwm/core.c:87
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff81477a42)
Location: drivers/pwm/core.c:88
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff81498da2)
Location: drivers/pwm/core.c:88
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814a25e0)
Location: drivers/pwm/core.c:88
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff814a25e0-ffffffff814a2688: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814e1330)
Location: drivers/pwm/core.c:88
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff814e1330-ffffffff814e13d8: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81510c30)
Location: drivers/pwm/core.c:88
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81510c30-ffffffff81510cde: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff815262e0)
Location: drivers/pwm/core.c:88
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff815262e0-ffffffff8152638e: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81555220)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81555220-ffffffff815552c3: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81576860)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81576860-ffffffff81576903: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161b230)
Location: drivers/pwm/core.c:79
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8161b230-ffffffff8161b2d3: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816419c0)
Location: drivers/pwm/core.c:79
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff816419c0-ffffffff81641a63: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816248d0)
Location: drivers/pwm/core.c:69
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff816248d0-ffffffff81624973: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81693e70)
Location: drivers/pwm/core.c:69
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81693e70-ffffffff81693f13: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b4990)
Location: drivers/pwm/core.c:69
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff817b4990-ffffffff817b4a3f: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cedb0)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff818cedb0-ffffffff818cee5f: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81911df0)
Location: drivers/pwm/core.c:62
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81911df0-ffffffff81911e9f: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81959bc0)
Location: drivers/pwm/core.c:35
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81959bc0-ffffffff81959c9f: pwmchip_find_by_name (STB_LOCAL)
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
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffff8000106d7ab0)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffff8000106d7ab0-ffff8000106d7b8c: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c0874b28)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
c0874b28-c0874be4: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c00000000084ec70)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
c00000000084ec70-c00000000084ef70: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffe0004b13b8)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffe0004b13b8-ffffffe0004b147a: pwmchip_find_by_name (STB_LOCAL)
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
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156b670)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8156b670-ffffffff8156b713: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156a5b0)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8156a5b0-ffffffff8156a653: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pwm_chip *pwmchip_find_by_name(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81584ab0)
Location: drivers/pwm/core.c:76
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81584ab0-ffffffff81584b53: pwmchip_find_by_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
