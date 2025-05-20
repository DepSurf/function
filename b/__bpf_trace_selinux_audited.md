# Function: <code>__bpf_trace_selinux_audited</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ca860)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff814ca860-ffffffff814ca86b: __bpf_trace_selinux_audited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d0ea0)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff814d0ea0-ffffffff814d0eab: __bpf_trace_selinux_audited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81529bd0)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff81529bd0-ffffffff81529bdb: __bpf_trace_selinux_audited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815bf3b0)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff815bf3b0-ffffffff815bf3ca: __bpf_trace_selinux_audited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166b7f0)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff8166b7f0-ffffffff8166b80a: __bpf_trace_selinux_audited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a3f70)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff816a3f70-ffffffff816a3f8a: __bpf_trace_selinux_audited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_selinux_audited(void *__data, struct selinux_audit_data *sad, char *scontext, char *tcontext, const char *tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e09d0)
Location: include/trace/events/avc.h:14
Inline: False
```
**Symbols:**

```
ffffffff816e09d0-ffffffff816e09ea: __bpf_trace_selinux_audited (STB_LOCAL)
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
