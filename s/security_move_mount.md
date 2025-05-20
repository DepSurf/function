# Function: <code>security_move_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cff0)
Location: security/security.c:946
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff8143cff0-ffffffff8143d03d: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456a90)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff81456a90-ffffffff81456ad4: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a98a0)
Location: security/security.c:1128
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff814a98a0-ffffffff814a98e4: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6ea0)
Location: security/security.c:1130
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff814c6ea0-ffffffff814c6ee4: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd060)
Location: security/security.c:1175
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff814cd060-ffffffff814cd0a4: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815261e0)
Location: security/security.c:1175
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff815261e0-ffffffff81526224: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba610)
Location: security/security.c:1179
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff815ba610-ffffffff815ba66d: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665fb0)
Location: security/security.c:1177
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff81665fb0-ffffffff8166600d: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e5a0)
Location: security/security.c:1594
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_move_mount
```
**Symbols:**

```
ffffffff8169e5a0-ffffffff8169e5fd: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816daef0)
Location: security/security.c:1647
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_move_mount
```
**Symbols:**

```
ffffffff816daef0-ffffffff816daf4d: security_move_mount (STB_GLOBAL)
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
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542440)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_move_mount
```
**Symbols:**

```
ffff800010542440-ffff8000105424a0: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f83ec)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_move_mount
```
**Symbols:**

```
c06f83ec-c06f8448: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000695700)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_move_mount
```
**Symbols:**

```
c000000000695700-c0000000006957bc: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ed9e)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_move_mount
```
**Symbols:**

```
ffffffe00039ed9e-ffffffe00039ede2: security_move_mount (STB_GLOBAL)
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
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f070)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff8144f070-ffffffff8144f0b4: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fac0)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff8143fac0-ffffffff8143fb04: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b110)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff8144b110-ffffffff8144b154: security_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_move_mount(const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814624e0)
Location: security/security.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff814624e0-ffffffff81462524: security_move_mount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
