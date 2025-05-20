# Function: <code>security_path_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_mkdir(struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133bfc0)
Location: security/security.c:422
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
```
**Symbols:**

```
ffffffff8133bfc0-ffffffff8133c02d: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371590)
Location: security/security.c:423
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
```
**Symbols:**

```
ffffffff81371590-ffffffff813715fd: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387ec0)
Location: security/security.c:432
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
```
**Symbols:**

```
ffffffff81387ec0-ffffffff81387f2d: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139cdf0)
Location: security/security.c:1037
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
```
**Symbols:**

```
ffffffff8139cdf0-ffffffff8139ce5d: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2630)
Location: security/security.c:986
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
```
**Symbols:**

```
ffffffff813c2630-ffffffff813c26a3: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2770)
Location: security/security.c:528
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff813f2770-ffffffff813f27d0: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dc10)
Location: security/security.c:1049
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff8140dc10-ffffffff8140dc70: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bac0)
Location: security/security.c:1063
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff8143bac0-ffffffff8143bb2b: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455810)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff81455810-ffffffff81455870: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8040)
Location: security/security.c:1251
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff814a8040-ffffffff814a80a0: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c55c0)
Location: security/security.c:1253
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff814c55c0-ffffffff814c5620: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbab0)
Location: security/security.c:1306
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff814cbab0-ffffffff814cbb10: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815247b0)
Location: security/security.c:1306
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff815247b0-ffffffff81524810: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8910)
Location: security/security.c:1326
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff815b8910-ffffffff815b8997: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81663f60)
Location: security/security.c:1324
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff81663f60-ffffffff81663fe7: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c3a0)
Location: security/security.c:1843
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff8169c3a0-ffffffff8169c427: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9040)
Location: security/security.c:1916
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
```
**Symbols:**

```
ffffffff816d9040-ffffffff816d90c7: security_path_mkdir (STB_GLOBAL)
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
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540d58)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffff800010540d58-ffff800010540dcc: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6d98)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
c06f6d98-c06f6e10: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000692f00)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
c000000000692f00-c000000000692fc8: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039dc46)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffe00039dc46-ffffffe00039dca0: security_path_mkdir (STB_GLOBAL)
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
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ddf0)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff8144ddf0-ffffffff8144de50: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e840)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff8143e840-ffffffff8143e8a0: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449e90)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff81449e90-ffffffff81449ef0: security_path_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_mkdir(const struct path *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461260)
Location: security/security.c:1103
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff81461260-ffffffff814612c0: security_path_mkdir (STB_GLOBAL)
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
<code>struct path *dir</code> ➡️ <code>const struct path *dir</code>
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
