# Function: <code>audit_buffer_aux_new</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_buffer_aux_new(struct audit_buffer *ab, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811df600)
Location: kernel/audit.c:2193
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
```
**Symbols:**

```
ffffffff811df600-ffffffff811df70b: audit_buffer_aux_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_buffer_aux_new(struct audit_buffer *ab, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812252e0)
Location: kernel/audit.c:2191
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
```
**Symbols:**

```
ffffffff812252e0-ffffffff812253eb: audit_buffer_aux_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_buffer_aux_new(struct audit_buffer *ab, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123b8b0)
Location: kernel/audit.c:2191
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
```
**Symbols:**

```
ffffffff8123b8b0-ffffffff8123b9bb: audit_buffer_aux_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_buffer_aux_new(struct audit_buffer *ab, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81255770)
Location: kernel/audit.c:2209
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
```
**Symbols:**

```
ffffffff81255770-ffffffff8125587b: audit_buffer_aux_new (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
