# Function: <code>d_absolute_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812261c0)
Location: fs/dcache.c:3005
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff812261c0-ffffffff81226251: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124e860)
Location: fs/dcache.c:3172
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff8124e860-ffffffff8124e8f1: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261870)
Location: fs/dcache.c:3182
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81261870-ffffffff81261901: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126f0f0)
Location: fs/dcache.c:3212
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff8126f0f0-ffffffff8126f190: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81291a10)
Location: fs/dcache.c:3224
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81291a10-ffffffff81291ab0: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812d40f0)
Location: fs/d_path.c:191
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff812d40f0-ffffffff812d4199: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812e94c0)
Location: fs/d_path.c:191
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/apparmor/path.c:aa_path_name
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff812e94c0-ffffffff812e9569: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81307d50)
Location: fs/d_path.c:191
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81307d50-ffffffff81307df9: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8131adf0)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff8131adf0-ffffffff8131ae99: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81354b10)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81354b10-ffffffff81354b9a: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81361430)
Location: fs/d_path.c:197
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81361430-ffffffff813614ba: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81367f10)
Location: fs/d_path.c:197
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81367f10-ffffffff81367f9a: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813b6b50)
Location: fs/d_path.c:228
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff813b6b50-ffffffff813b6bea: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8143c170)
Location: fs/d_path.c:226
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff8143c170-ffffffff8143c219: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814ca800)
Location: fs/d_path.c:226
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff814ca800-ffffffff814ca8a9: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81500a40)
Location: fs/d_path.c:227
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81500a40-ffffffff81500ae9: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81535660)
Location: fs/d_path.c:227
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81535660-ffffffff81535709: d_absolute_path (STB_GLOBAL)
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
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffff8000103d2140)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffff8000103d2140-ffff8000103d21fc: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c05acb50)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
c05acb50-c05acc04: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c0000000004d4c10)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
c0000000004d4c10-c0000000004d4cf0: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffe00028d3fc)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffe00028d3fc-ffffffe00028d486: d_absolute_path (STB_GLOBAL)
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
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813133d0)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff813133d0-ffffffff81313479: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81303fe0)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81303fe0-ffffffff81304089: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813111c0)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff813111c0-ffffffff81311269: d_absolute_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *d_absolute_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81322a10)
Location: fs/d_path.c:193
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/integrity/ima/ima_api.c:ima_d_path
```
**Symbols:**

```
ffffffff81322a10-ffffffff81322ab9: d_absolute_path (STB_GLOBAL)
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
