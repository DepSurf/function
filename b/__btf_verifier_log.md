# Function: <code>__btf_verifier_log</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c6b80)
Location: kernel/bpf/btf.c:469
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811c6b80-ffffffff811c6bea: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811d9930)
Location: kernel/bpf/btf.c:589
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811d9930-ffffffff811d999a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ee6b0)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811ee6b0-ffffffff811ee71a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fadf0)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811fadf0-ffffffff811fae5a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8121f760)
Location: kernel/bpf/btf.c:679
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff8121f760-ffffffff8121f7ca: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223250)
Location: kernel/bpf/btf.c:1264
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff81223250-ffffffff812232ba: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227d00)
Location: kernel/bpf/btf.c:1265
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff81227d00-ffffffff81227d6a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8125fff0)
Location: kernel/bpf/btf.c:1265
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff8125fff0-ffffffff8126005a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812aa850)
Location: kernel/bpf/btf.c:1360
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff812aa850-ffffffff812aa8d6: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130a070)
Location: kernel/bpf/btf.c:1364
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff8130a070-ffffffff8130a0f6: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813391a0)
Location: kernel/bpf/btf.c:1383
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff813391a0-ffffffff81339226: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135f2d0)
Location: kernel/bpf/btf.c:1384
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff8135f2d0-ffffffff8135f356: __btf_verifier_log (STB_LOCAL)
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
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010280fb0)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffff800010280fb0-ffff800010281048: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b19f4)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
c04b19f4-c04b1a58: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032b4a0)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
c00000000032b4a0-c00000000032b4f0: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b75d4)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffe0001b75d4-ffffffe0001b761c: __btf_verifier_log (STB_LOCAL)
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
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3410)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811f3410-ffffffff811f347a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e6160)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811e6160-ffffffff811e61ca: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f11e0)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811f11e0-ffffffff811f124a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log *log, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ff6f0)
Location: kernel/bpf/btf.c:664
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
**Symbols:**

```
ffffffff811ff6f0-ffffffff811ff75a: __btf_verifier_log (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
