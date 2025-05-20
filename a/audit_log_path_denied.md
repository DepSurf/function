# Function: <code>audit_log_path_denied</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118a020)
Location: kernel/audit.c:2313
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff8118a020-ffffffff8118a0c8: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187330)
Location: kernel/audit.c:2330
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff81187330-ffffffff811873d8: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188260)
Location: kernel/audit.c:2330
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff81188260-ffffffff81188308: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b0780)
Location: kernel/audit.c:2369
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff811b0780-ffffffff811b0828: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2940)
Location: kernel/audit.c:2415
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff811e2940-ffffffff811e29e2: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81228810)
Location: kernel/audit.c:2413
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff81228810-ffffffff812288b2: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ee10)
Location: kernel/audit.c:2413
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff8123ee10-ffffffff8123eeb2: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char *operation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258c90)
Location: kernel/audit.c:2435
Inline: False
Direct callers:
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
**Symbols:**

```
ffffffff81258c90-ffffffff81258d32: audit_log_path_denied (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
