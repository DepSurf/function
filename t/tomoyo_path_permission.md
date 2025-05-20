# Function: <code>tomoyo_path_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8136ed20)
Location: security/tomoyo/file.c:558
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
```
**Symbols:**

```
ffffffff8136ed20-ffffffff8136edaa: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813a5000)
Location: security/tomoyo/file.c:558
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff813a5000-ffffffff813a5091: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813bbb80)
Location: security/tomoyo/file.c:558
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff813bbb80-ffffffff813bbc11: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813d2480)
Location: security/tomoyo/file.c:558
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff813d2480-ffffffff813d2511: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813f8990)
Location: security/tomoyo/file.c:559
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff813f8990-ffffffff813f8a21: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81429980)
Location: security/tomoyo/file.c:559
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81429980-ffffffff81429a11: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81446240)
Location: security/tomoyo/file.c:559
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81446240-ffffffff814462d1: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81473e60)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81473e60-ffffffff81473eea: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8148dc00)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff8148dc00-ffffffff8148dc8a: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814e4c60)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff814e4c60-ffffffff814e4cea: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81502060)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81502060-ffffffff815020ea: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81508c30)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81508c30-ffffffff81508cba: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81565ed0)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81565ed0-ffffffff81565fa5: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816018a0)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff816018a0-ffffffff81601981: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b28f0)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff816b28f0-ffffffff816b29d1: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816eb300)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff816eb300-ffffffff816eb3e1: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff817280d0)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff817280d0-ffffffff817281b1: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffff800010581330)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffff800010581330-ffff800010581400: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0733610)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
c0733610-c07336c0: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0000000006efb50)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
c0000000006efb50-c0000000006efc80: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffe0003d1da0)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffe0003d1da0-ffffffe0003d1e54: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814861e0)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff814861e0-ffffffff8148626a: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81476c00)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81476c00-ffffffff81476c8a: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81482280)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81482280-ffffffff8148230a: tomoyo_path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_path_permission(struct tomoyo_request_info *r, u8 operation, const struct tomoyo_path_info *filename);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81499e10)
Location: security/tomoyo/file.c:573
Inline: True
Direct callers:
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_check_open_permission
```
**Symbols:**

```
ffffffff81499e10-ffffffff81499e9a: tomoyo_path_permission (STB_LOCAL)
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
