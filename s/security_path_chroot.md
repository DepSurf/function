# Function: <code>security_path_chroot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_chroot(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133d500)
Location: security/security.c:508
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
```
**Symbols:**

```
ffffffff8133d500-ffffffff8133d543: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372b30)
Location: security/security.c:509
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
```
**Symbols:**

```
ffffffff81372b30-ffffffff81372b73: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389460)
Location: security/security.c:518
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
```
**Symbols:**

```
ffffffff81389460-ffffffff813894a3: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e840)
Location: security/security.c:1123
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
```
**Symbols:**

```
ffffffff8139e840-ffffffff8139e883: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4290)
Location: security/security.c:1072
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
```
**Symbols:**

```
ffffffff813c4290-ffffffff813c42d9: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4740)
Location: security/security.c:614
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff813f4740-ffffffff813f477a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140fb10)
Location: security/security.c:1135
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff8140fb10-ffffffff8140fb4a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d130)
Location: security/security.c:1149
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff8143d130-ffffffff8143d171: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456c10)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff81456c10-ffffffff81456c4a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9a20)
Location: security/security.c:1337
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff814a9a20-ffffffff814a9a5a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7020)
Location: security/security.c:1339
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff814c7020-ffffffff814c705a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd460)
Location: security/security.c:1386
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff814cd460-ffffffff814cd49a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815263b0)
Location: security/security.c:1392
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff815263b0-ffffffff815263ea: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bab60)
Location: security/security.c:1399
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff815bab60-ffffffff815babad: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816665b0)
Location: security/security.c:1397
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff816665b0-ffffffff816665fd: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169eba0)
Location: security/security.c:2007
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff8169eba0-ffffffff8169ebed: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db4f0)
Location: security/security.c:2080
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff816db4f0-ffffffff816db53d: security_path_chroot (STB_GLOBAL)
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
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542608)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffff800010542608-ffff800010542658: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f85bc)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
c06f85bc-c06f8610: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000695a30)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
c000000000695a30-c000000000695ad8: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ef06)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffe00039ef06-ffffffe00039ef42: security_path_chroot (STB_GLOBAL)
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
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f1f0)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff8144f1f0-ffffffff8144f22a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fc40)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff8143fc40-ffffffff8143fc7a: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b290)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff8144b290-ffffffff8144b2ca: security_path_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_chroot(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462660)
Location: security/security.c:1189
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
```
**Symbols:**

```
ffffffff81462660-ffffffff8146269a: security_path_chroot (STB_GLOBAL)
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
