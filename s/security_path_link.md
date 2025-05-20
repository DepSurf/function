# Function: <code>security_path_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c160)
Location: security/security.c:455
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8133c160-ffffffff8133c1c8: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371730)
Location: security/security.c:456
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff81371730-ffffffff81371798: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388060)
Location: security/security.c:465
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff81388060-ffffffff813880c8: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139cf90)
Location: security/security.c:1070
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8139cf90-ffffffff8139cff8: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2810)
Location: security/security.c:1019
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff813c2810-ffffffff813c287e: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f28f0)
Location: security/security.c:561
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff813f28f0-ffffffff813f294b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dd90)
Location: security/security.c:1082
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff8140dd90-ffffffff8140ddeb: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bc60)
Location: security/security.c:1096
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff8143bc60-ffffffff8143bcc6: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455990)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff81455990-ffffffff814559eb: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a81c0)
Location: security/security.c:1284
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff814a81c0-ffffffff814a821b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5740)
Location: security/security.c:1286
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff814c5740-ffffffff814c579b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd2f0)
Location: security/security.c:1337
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff814cd2f0-ffffffff814cd34b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524930)
Location: security/security.c:1339
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff81524930-ffffffff8152498b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba950)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff815ba950-ffffffff815ba9d4: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81666360)
Location: security/security.c:1355
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff81666360-ffffffff816663e4: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e950)
Location: security/security.c:1913
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff8169e950-ffffffff8169e9d4: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db2a0)
Location: security/security.c:1986
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
```
**Symbols:**

```
ffffffff816db2a0-ffffffff816db324: security_path_link (STB_GLOBAL)
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
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540f28)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffff800010540f28-ffff800010540f9c: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6f68)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
c06f6f68-c06f6fdc: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693220)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
c000000000693220-c0000000006932e8: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039dd9e)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffe00039dd9e-ffffffe00039ddf6: security_path_link (STB_GLOBAL)
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
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144df70)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff8144df70-ffffffff8144dfcb: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e9c0)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff8143e9c0-ffffffff8143ea1b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a010)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff8144a010-ffffffff8144a06b: security_path_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_link(struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814613e0)
Location: security/security.c:1136
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
```
**Symbols:**

```
ffffffff814613e0-ffffffff8146143b: security_path_link (STB_GLOBAL)
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
<code>struct path *new_dir</code> ➡️ <code>const struct path *new_dir</code>
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
