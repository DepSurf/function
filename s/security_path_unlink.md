# Function: <code>security_path_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_unlink(struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c090)
Location: security/security.c:438
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8133c090-ffffffff8133c0f0: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371660)
Location: security/security.c:439
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff81371660-ffffffff813716c0: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387f90)
Location: security/security.c:448
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff81387f90-ffffffff81387ff0: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139cec0)
Location: security/security.c:1053
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8139cec0-ffffffff8139cf20: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2720)
Location: security/security.c:1002
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff813c2720-ffffffff813c2786: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2830)
Location: security/security.c:544
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff813f2830-ffffffff813f2885: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dcd0)
Location: security/security.c:1065
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8140dcd0-ffffffff8140dd25: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bb90)
Location: security/security.c:1079
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8143bb90-ffffffff8143bbee: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814558d0)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff814558d0-ffffffff81455925: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8100)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff814a8100-ffffffff814a8155: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5680)
Location: security/security.c:1269
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff814c5680-ffffffff814c56d5: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbb10)
Location: security/security.c:1321
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff814cbb10-ffffffff814cbb65: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524870)
Location: security/security.c:1322
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff81524870-ffffffff815248c5: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b89a0)
Location: security/security.c:1341
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff815b89a0-ffffffff815b8a16: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664000)
Location: security/security.c:1339
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff81664000-ffffffff81664076: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c440)
Location: security/security.c:1877
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8169c440-ffffffff8169c4b6: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d90e0)
Location: security/security.c:1950
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff816d90e0-ffffffff816d9156: security_path_unlink (STB_GLOBAL)
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
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540e40)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffff800010540e40-ffff800010540eb0: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6e80)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
c06f6e80-c06f6ef0: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693090)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
c000000000693090-c000000000693148: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039dcf2)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffe00039dcf2-ffffffe00039dd44: security_path_unlink (STB_GLOBAL)
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
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144deb0)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8144deb0-ffffffff8144df05: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e900)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff8143e900-ffffffff8143e955: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449f50)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff81449f50-ffffffff81449fa5: security_path_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_unlink(const struct path *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461320)
Location: security/security.c:1119
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
```
**Symbols:**

```
ffffffff81461320-ffffffff81461375: security_path_unlink (STB_GLOBAL)
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
