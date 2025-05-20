# Function: <code>security_path_chown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_chown(struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c2a0)
Location: security/security.c:500
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8133c2a0-ffffffff8133c30c: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371870)
Location: security/security.c:501
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff81371870-ffffffff813718dc: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813881a0)
Location: security/security.c:510
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff813881a0-ffffffff8138820c: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d1a0)
Location: security/security.c:1115
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8139d1a0-ffffffff8139d20c: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2a30)
Location: security/security.c:1064
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff813c2a30-ffffffff813c2aa2: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2ac0)
Location: security/security.c:606
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff813f2ac0-ffffffff813f2b1f: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140df60)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8140df60-ffffffff8140dfbf: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143be50)
Location: security/security.c:1141
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8143be50-ffffffff8143beba: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455b50)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff81455b50-ffffffff81455baf: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8380)
Location: security/security.c:1329
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff814a8380-ffffffff814a83df: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5910)
Location: security/security.c:1331
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff814c5910-ffffffff814c596f: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd400)
Location: security/security.c:1379
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff814cd400-ffffffff814cd45f: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524b00)
Location: security/security.c:1384
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff81524b00-ffffffff81524b5f: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815baad0)
Location: security/security.c:1392
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff815baad0-ffffffff815bab58: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81666510)
Location: security/security.c:1390
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff81666510-ffffffff81666598: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169eb00)
Location: security/security.c:1992
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8169eb00-ffffffff8169eb88: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db450)
Location: security/security.c:2065
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff816db450-ffffffff816db4d8: security_path_chown (STB_GLOBAL)
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
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541150)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffff800010541150-ffff8000105411c4: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7194)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
c06f7194-c06f720c: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006935f0)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
c0000000006935f0-c0000000006936b8: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039df34)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffe00039df34-ffffffe00039df8e: security_path_chown (STB_GLOBAL)
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
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e130)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8144e130-ffffffff8144e18f: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eb80)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8143eb80-ffffffff8143ebdf: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a1d0)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8144a1d0-ffffffff8144a22f: security_path_chown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_chown(const struct path *path, kuid_t uid, kgid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814615a0)
Location: security/security.c:1181
Inline: False
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff814615a0-ffffffff814615ff: security_path_chown (STB_GLOBAL)
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
