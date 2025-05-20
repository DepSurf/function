# Function: <code>audit_log_object_context</code>

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
int audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811877d0)
Location: kernel/audit.c:2183
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff811877d0-ffffffff8118795d: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184b40)
Location: kernel/audit.c:2200
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff81184b40-ffffffff81184ccd: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811859d0)
Location: kernel/audit.c:2200
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff811859d0-ffffffff81185b60: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811addb0)
Location: kernel/audit.c:2239
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff811addb0-ffffffff811adf40: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0cd0)
Location: kernel/audit.c:2290
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff811e0cd0-ffffffff811e0e8e: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226af0)
Location: kernel/audit.c:2288
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff81226af0-ffffffff81226cae: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123d0d0)
Location: kernel/audit.c:2288
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff8123d0d0-ffffffff8123d2b2: audit_log_object_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void audit_log_object_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:2308
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff821b6c40-ffffffff821b6c54: audit_log_object_context.cold (STB_LOCAL)
ffffffff81257000-ffffffff812571ea: audit_log_object_context (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
