# Function: <code>d_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225220)
Location: fs/dcache.c:3070
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/file.c:ext4_file_open
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81225220-ffffffff8122535b: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b950)
Location: fs/dcache.c:3237
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/file.c:ext4_file_open
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff8124b950-ffffffff8124ba8b: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e930)
Location: fs/dcache.c:3247
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/file.c:ext4_file_open
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff8125e930-ffffffff8125ea6b: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c1a0)
Location: fs/dcache.c:3277
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/file.c:ext4_file_open
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff8126c1a0-ffffffff8126c2c7: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128fa90)
Location: fs/dcache.c:3289
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/file.c:ext4_file_open
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff8128fa90-ffffffff8128fbba: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812d3b70)
Location: fs/d_path.c:256
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff812d3b70-ffffffff812d3ca6: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812e8dc0)
Location: fs/d_path.c:256
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff812e8dc0-ffffffff812e8ef6: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81307650)
Location: fs/d_path.c:256
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81307650-ffffffff81307785: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8131a6c0)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff8131a6c0-ffffffff8131a7f5: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81354960)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:do_proc_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81354960-ffffffff81354a9b: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81361270)
Location: fs/d_path.c:262
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:do_proc_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81361270-ffffffff813613b8: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81367d50)
Location: fs/d_path.c:262
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81367d50-ffffffff81367e98: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813b6590)
Location: fs/d_path.c:266
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff813b6590-ffffffff813b66c8: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8143bb30)
Location: fs/d_path.c:264
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff8143bb30-ffffffff8143bc97: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814ca150)
Location: fs/d_path.c:264
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff814ca150-ffffffff814ca2b7: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81500390)
Location: fs/d_path.c:265
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81500390-ffffffff815004f7: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81534fb0)
Location: fs/d_path.c:265
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info
  - kernel/trace/bpf_trace.c:bpf_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/ext4/file.c:ext4_sample_last_mounted
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81534fb0-ffffffff81535117: d_path (STB_GLOBAL)
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
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffff8000103d1a00)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffff8000103d1a00-ffff8000103d1b5c: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c05ac740)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:__se_sys_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
c05ac740-c05ac8c8: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c0000000004d4490)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
c0000000004d4490-c0000000004d4614: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffe00028d078)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:__se_sys_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffe00028d078-ffffffe00028d1d6: d_path (STB_GLOBAL)
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
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81312ca0)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81312ca0-ffffffff81312dd5: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813038b0)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff813038b0-ffffffff813039e5: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81310a90)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff81310a90-ffffffff81310bc5: d_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *d_path(const struct path *path, char *buf, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813222b0)
Location: fs/d_path.c:258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_d_path
  - fs/open.c:file_path
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/seq_file.c:seq_path
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:do_lookup_dcookie
  - lib/seq_buf.c:seq_buf_path
```
**Symbols:**

```
ffffffff813222b0-ffffffff813223f1: d_path (STB_GLOBAL)
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
