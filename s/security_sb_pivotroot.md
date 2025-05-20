# Function: <code>security_sb_pivotroot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sb_pivotroot(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133d420)
Location: security/security.c:316
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff8133d420-ffffffff8133d46f: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372a50)
Location: security/security.c:317
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff81372a50-ffffffff81372a9f: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389380)
Location: security/security.c:317
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff81389380-ffffffff813893cf: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e720)
Location: security/security.c:894
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff8139e720-ffffffff8139e76f: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4130)
Location: security/security.c:842
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff813c4130-ffffffff813c4185: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4660)
Location: security/security.c:410
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff813f4660-ffffffff813f46a4: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f9e0)
Location: security/security.c:903
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff8140f9e0-ffffffff8140fa24: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cfa0)
Location: security/security.c:912
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff8143cfa0-ffffffff8143cfed: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456a40)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff81456a40-ffffffff81456a84: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9850)
Location: security/security.c:1094
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814a9850-ffffffff814a9894: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6e50)
Location: security/security.c:1096
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814c6e50-ffffffff814c6e94: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd010)
Location: security/security.c:1141
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814cd010-ffffffff814cd054: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526190)
Location: security/security.c:1141
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff81526190-ffffffff815261d4: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba5b0)
Location: security/security.c:1153
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff815ba5b0-ffffffff815ba60d: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665f40)
Location: security/security.c:1151
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff81665f40-ffffffff81665f9d: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e530)
Location: security/security.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff8169e530-ffffffff8169e58d: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dae80)
Location: security/security.c:1589
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff816dae80-ffffffff816daedd: security_sb_pivotroot (STB_GLOBAL)
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
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105423e0)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
```
**Symbols:**

```
ffff8000105423e0-ffff800010542440: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8390)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
```
**Symbols:**

```
c06f8390-c06f83ec: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000695640)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
```
**Symbols:**

```
c000000000695640-c0000000006956fc: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ed5a)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
```
**Symbols:**

```
ffffffe00039ed5a-ffffffe00039ed9e: security_sb_pivotroot (STB_GLOBAL)
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
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f020)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff8144f020-ffffffff8144f064: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fa70)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff8143fa70-ffffffff8143fab4: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b0c0)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff8144b0c0-ffffffff8144b104: security_sb_pivotroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sb_pivotroot(const struct path *old_path, const struct path *new_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462490)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
**Symbols:**

```
ffffffff81462490-ffffffff814624d4: security_sb_pivotroot (STB_GLOBAL)
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
<code>struct path *old_path</code> ➡️ <code>const struct path *old_path</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path *new_path</code> ➡️ <code>const struct path *new_path</code>
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
