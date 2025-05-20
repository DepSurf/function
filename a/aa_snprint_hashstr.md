# Function: <code>aa_snprint_hashstr</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff813f4160)
Location: security/apparmor/crypto.c:32
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff813f4160-ffffffff813f41d1: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff8141c350)
Location: security/apparmor/crypto.c:32
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff8141c350-ffffffff8141c3c1: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff8144e5f0)
Location: security/apparmor/crypto.c:32
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff8144e5f0-ffffffff8144e65e: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff8146b5f0)
Location: security/apparmor/crypto.c:32
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff8146b5f0-ffffffff8146b65e: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff814985e0)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff814985e0-ffffffff8149863d: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff814b2510)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff814b2510-ffffffff814b256d: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff815117be)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff81511730-ffffffff81511789: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff8152e5ee)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff8152e560-ffffffff8152e5b9: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff815348de)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff81534850-ffffffff815348a9: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff81592e4e)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff81592dc0-ffffffff81592e19: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff81634ccf)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff81634c30-ffffffff81634c95: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff816eb8cf)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff816eb820-ffffffff816eb885: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff81725cff)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff81725c50-ffffffff81725cb5: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff81766eef)
Location: security/apparmor/crypto.c:28
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff81766e40-ffffffff81766ea5: aa_snprint_hashstr (STB_GLOBAL)
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
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffff8000105a9eb8)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffff8000105a9eb8-ffff8000105a9f34: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (c0759c00)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
c0759c00-c0759c5c: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (c000000000727520)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
c000000000727520-c0000000007275d8: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffe0003f2e5e)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffe0003f2e5e-ffffffe0003f2ee2: aa_snprint_hashstr (STB_GLOBAL)
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
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff814aaaf0)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff814aaaf0-ffffffff814aab4d: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff8149b510)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff8149b510-ffffffff8149b56d: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff814a6b90)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff814a6b90-ffffffff814a6bed: aa_snprint_hashstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_snprint_hashstr(char *out, unsigned char *hash, unsigned int hsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/crypto.c (ffffffff814bf480)
Location: security/apparmor/crypto.c:28
Inline: False
Direct callers:
  - security/apparmor/crypto.c:aa_asprint_hashstr
```
**Symbols:**

```
ffffffff814bf480-ffffffff814bf4dd: aa_snprint_hashstr (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
