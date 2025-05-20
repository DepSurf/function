# Function: <code>tomoyo_check_open_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8136f4c0)
Location: security/tomoyo/file.c:735
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff8136f4c0-ffffffff8136f63b: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813a57e0)
Location: security/tomoyo/file.c:735
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff813a57e0-ffffffff813a5952: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813bc360)
Location: security/tomoyo/file.c:735
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff813bc360-ffffffff813bc4d2: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813d2c70)
Location: security/tomoyo/file.c:735
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff813d2c70-ffffffff813d2e09: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813f9180)
Location: security/tomoyo/file.c:736
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff813f9180-ffffffff813f9319: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8142a160)
Location: security/tomoyo/file.c:736
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff8142a160-ffffffff8142a2f9: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81446a30)
Location: security/tomoyo/file.c:736
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff81446a30-ffffffff81446bc9: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81474630)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff81474630-ffffffff814747e7: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8148e3d0)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff8148e3d0-ffffffff8148e587: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814e5660)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff814e5660-ffffffff814e5815: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81502a60)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff81502a60-ffffffff81502c15: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81509630)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff81509630-ffffffff815097e2: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81566a20)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff81566a20-ffffffff81566bd2: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816024e0)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff816024e0-ffffffff816026ac: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b3630)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff816b3630-ffffffff816b37fc: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816ebff0)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff816ebff0-ffffffff816ec1bc: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81728dc0)
Location: security/tomoyo/file.c:753
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
**Symbols:**

```
ffffffff81728dc0-ffffffff81728f8c: tomoyo_check_open_permission (STB_GLOBAL)
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
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffff800010581d90)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffff800010581d90-ffff800010581f30: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0733cb8)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
c0733cb8-c0733e6c: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0000000006f0500)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
c0000000006f0500-c0000000006f06f8: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffe0003d240c)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffe0003d240c-ffffffe0003d2562: tomoyo_check_open_permission (STB_GLOBAL)
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
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814869b0)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff814869b0-ffffffff81486b67: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814773d0)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff814773d0-ffffffff81477587: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81482a50)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff81482a50-ffffffff81482c07: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_check_open_permission(struct tomoyo_domain_info *domain, const struct path *path, const int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8149a5e0)
Location: security/tomoyo/file.c:753
Inline: False
```
**Symbols:**

```
ffffffff8149a5e0-ffffffff8149a797: tomoyo_check_open_permission (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
