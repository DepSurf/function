# Function: <code>audit_log_d_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81122140)
Location: kernel/audit.c:1630
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81122140-ffffffff8112220f: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a070)
Location: kernel/audit.c:1641
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8112a070-ffffffff8112a13f: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133d90)
Location: kernel/audit.c:1780
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81133d90-ffffffff81133e5f: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135270)
Location: kernel/audit.c:1959
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81135270-ffffffff81135375: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141fc0)
Location: kernel/audit.c:1967
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81141fc0-ffffffff8114207f: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150980)
Location: kernel/audit.c:2020
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff81150980-ffffffff81150a41: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d620)
Location: kernel/audit.c:2017
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff8115d620-ffffffff8115d6f0: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169d40)
Location: kernel/audit.c:2017
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff81169d40-ffffffff81169e09: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175be0)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff81175be0-ffffffff81175ca9: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188380)
Location: kernel/audit.c:2099
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff81188380-ffffffff81188444: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811856e0)
Location: kernel/audit.c:2116
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff811856e0-ffffffff8118579f: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811866d0)
Location: kernel/audit.c:2116
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff811866d0-ffffffff8118678f: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aeac0)
Location: kernel/audit.c:2155
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff811aeac0-ffffffff811aebb7: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0b00)
Location: kernel/audit.c:2137
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff811e0b00-ffffffff811e0c0b: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812268f0)
Location: kernel/audit.c:2135
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812268f0-ffffffff812269fe: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ced0)
Location: kernel/audit.c:2135
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff8123ced0-ffffffff8123cfde: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81256de0)
Location: kernel/audit.c:2153
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff81256de0-ffffffff81256f0e: audit_log_d_path (STB_GLOBAL)
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
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eab78)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffff8000101eab78-ffff8000101eac4c: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a800)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
c042a800-c042a8bc: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025bfa0)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
c00000000025bfa0-c00000000025c0b0: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f4c8)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffe00015f4c8-ffffffe00015f5a4: audit_log_d_path (STB_GLOBAL)
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
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e200)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff8116e200-ffffffff8116e2c9: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811613a0)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff811613a0-ffffffff81161469: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116bfd0)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff8116bfd0-ffffffff8116c099: audit_log_d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_d_path(struct audit_buffer *ab, const char *prefix, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179790)
Location: kernel/audit.c:2019
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path_exe
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff81179790-ffffffff81179859: audit_log_d_path (STB_GLOBAL)
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
