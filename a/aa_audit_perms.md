# Function: <code>aa_audit_perms</code>

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
void aa_audit_perms(struct audit_buffer *ab, struct common_audit_data *sa, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816118f0)
Location: security/apparmor/lib.c:280
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
```
**Symbols:**

```
ffffffff816118f0-ffffffff816119cf: aa_audit_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_audit_perms(struct audit_buffer *ab, struct apparmor_audit_data *ad, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c45e0)
Location: security/apparmor/lib.c:372
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
```
**Symbols:**

```
ffffffff816c45e0-ffffffff816c46af: aa_audit_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_audit_perms(struct audit_buffer *ab, struct apparmor_audit_data *ad, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fd1b0)
Location: security/apparmor/lib.c:372
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
```
**Symbols:**

```
ffffffff816fd1b0-ffffffff816fd27f: aa_audit_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_audit_perms(struct audit_buffer *ab, struct apparmor_audit_data *ad, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a710)
Location: security/apparmor/lib.c:374
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
```
**Symbols:**

```
ffffffff8173a710-ffffffff8173a7df: aa_audit_perms (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data *ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data *sa</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
