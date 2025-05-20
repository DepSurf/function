# Function: <code>tomoyo_get_local_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813726f0)
Location: security/tomoyo/realpath.c:147
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813726f0-ffffffff8137292c: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813a8b00)
Location: security/tomoyo/realpath.c:147
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813a8b00-ffffffff813a8d48: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813bf690)
Location: security/tomoyo/realpath.c:147
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813bf690-ffffffff813bf8cb: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813d5f60)
Location: security/tomoyo/realpath.c:147
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813d5f60-ffffffff813d6195: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813fc480)
Location: security/tomoyo/realpath.c:148
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813fc480-ffffffff813fc6b5: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:148
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8142d3e0-ffffffff8142d5e6: tomoyo_get_local_path (STB_LOCAL)
ffffffff8142d9a4-ffffffff8142d9bc: tomoyo_get_local_path.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:148
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81449d30-ffffffff81449f36: tomoyo_get_local_path (STB_LOCAL)
ffffffff8144a2f4-ffffffff8144a30c: tomoyo_get_local_path.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81477990-ffffffff81477ba3: tomoyo_get_local_path (STB_LOCAL)
ffffffff81477f84-ffffffff81477f9c: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81491730-ffffffff81491943: tomoyo_get_local_path (STB_LOCAL)
ffffffff81491c94-ffffffff81491cac: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff814e8b20-ffffffff814e8d37: tomoyo_get_local_path (STB_LOCAL)
ffffffff814e9094-ffffffff814e90ac: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81505e60-ffffffff81506077: tomoyo_get_local_path (STB_LOCAL)
ffffffff81bf14a5-ffffffff81bf14bd: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8150c990-ffffffff8150cbbc: tomoyo_get_local_path (STB_LOCAL)
ffffffff81be3632-ffffffff81be364a: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8156a4c0-ffffffff8156a6ec: tomoyo_get_local_path (STB_LOCAL)
ffffffff81cd6161-ffffffff81cd6179: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81606460-ffffffff816066a0: tomoyo_get_local_path (STB_LOCAL)
ffffffff81e88f47-ffffffff81e88f5f: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816b78d0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff816b78d0-ffffffff816b7b28: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816f02a0)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff816f02a0-ffffffff816f04f8: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8172d070)
Location: security/tomoyo/realpath.c:153
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8172d070-ffffffff8172d2c8: tomoyo_get_local_path (STB_LOCAL)
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
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffff800010585de8)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffff800010585de8-ffff80001058602c: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (c073772c)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
c073772c-c0737994: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (c0000000006f59a0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
c0000000006f59a0-c0000000006f5ccc: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffe0003d5800)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffe0003d5800-ffffffe0003d59c2: tomoyo_get_local_path (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81489d10-ffffffff81489f23: tomoyo_get_local_path (STB_LOCAL)
ffffffff8148a274-ffffffff8148a28c: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8147a730-ffffffff8147a943: tomoyo_get_local_path (STB_LOCAL)
ffffffff8147ac94-ffffffff8147acac: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81485db0-ffffffff81485fc3: tomoyo_get_local_path (STB_LOCAL)
ffffffff81486314-ffffffff8148632c: tomoyo_get_local_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
char *tomoyo_get_local_path(struct dentry *dentry, const char * buffer, const int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (0)
Location: security/tomoyo/realpath.c:152
Inline: False
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8149d8f0-ffffffff8149db03: tomoyo_get_local_path (STB_LOCAL)
ffffffff8149de54-ffffffff8149de6c: tomoyo_get_local_path.cold (STB_LOCAL)
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
