# Function: <code>audit_log_link_denied</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation, struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811239e0)
Location: kernel/audit.c:1924
Inline: False
Direct callers:
  - fs/namei.c:may_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff811239e0-ffffffff81123ab3: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation, struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112b9a0)
Location: kernel/audit.c:1945
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff8112b9a0-ffffffff8112ba73: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation, const struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811356c0)
Location: kernel/audit.c:2084
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff811356c0-ffffffff81135793: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation, const struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81136c70)
Location: kernel/audit.c:2251
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff81136c70-ffffffff81136d43: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation, const struct path *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81143970)
Location: kernel/audit.c:2259
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff81143970-ffffffff81143a43: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811523c0)
Location: kernel/audit.c:2311
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff811523c0-ffffffff8115244d: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115f070)
Location: kernel/audit.c:2308
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8115f070-ffffffff8115f0f5: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b3f0)
Location: kernel/audit.c:2161
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8116b3f0-ffffffff8116b474: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811772d0)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff811772d0-ffffffff81177354: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec288)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffff8000101ec288-ffff8000101ec310: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042be94)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
c042be94-c042bf30: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025dc00)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
c00000000025dc00-c00000000025dcc8: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe0001609b2)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffe0001609b2-ffffffe000160a38: audit_log_link_denied (STB_GLOBAL)
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
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116f8f0)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8116f8f0-ffffffff8116f974: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81162a90)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff81162a90-ffffffff81162b14: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d6c0)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8116d6c0-ffffffff8116d744: audit_log_link_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_link_denied(const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117aeb0)
Location: kernel/audit.c:2163
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8117aeb0-ffffffff8117af34: audit_log_link_denied (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *link</code> ➡️ <code>const struct path *link</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct path *link</code>
</li>
</ul>
</details>
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
