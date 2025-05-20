# Function: <code>bpf_verifier_vlog</code>

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
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b78d0)
Location: kernel/bpf/verifier.c:196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811b78d0-ffffffff811b79bd: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6ea0)
Location: kernel/bpf/verifier.c:241
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811c6ea0-ffffffff811c6f8d: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9140)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811d9140-ffffffff811d922c: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5830)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811e5830-ffffffff811e5923: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:268
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff812138e4-ffffffff812138f8: bpf_verifier_vlog.cold (STB_LOCAL)
ffffffff81205170-ffffffff8120526b: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff81be6536-ffffffff81be654a: bpf_verifier_vlog.cold (STB_LOCAL)
ffffffff812052c0-ffffffff812053bb: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff81bd821e-ffffffff81bd8232: bpf_verifier_vlog.cold (STB_LOCAL)
ffffffff81205c50-ffffffff81205d4b: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:292
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff81cb7d3e-ffffffff81cb7d6d: bpf_verifier_vlog.cold (STB_LOCAL)
ffffffff81238a50-ffffffff81238b7a: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:293
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff81e68eca-ffffffff81e68f03: bpf_verifier_vlog.cold (STB_LOCAL)
ffffffff8127cea0-ffffffff8127d06f: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:294
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff8205fc41-ffffffff8205fc56: bpf_verifier_vlog.cold (STB_LOCAL)
ffffffff812d3c80-ffffffff812d3e8c: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff813223e0)
Location: kernel/bpf/log.c:57
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/log.c:bpf_log
  - kernel/bpf/log.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff813223e0-ffffffff81322718: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff81344db0)
Location: kernel/bpf/log.c:59
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/log.c:verbose_linfo
  - kernel/bpf/log.c:bpf_log
  - kernel/bpf/log.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff81344db0-ffffffff813450e8: bpf_verifier_vlog (STB_GLOBAL)
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
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102689c8)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffff8000102689c8-ffff800010268c24: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049ae20)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
c049ae20-c049af90: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030e750)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
c00000000030e750-c00000000030e8c4: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a3b74)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffe0001a3b74-ffffffe0001a3c68: bpf_verifier_vlog (STB_GLOBAL)
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
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dde50)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811dde50-ffffffff811ddf43: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d0c10)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811d0c10-ffffffff811d0d03: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dbc20)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811dbc20-ffffffff811dbd13: bpf_verifier_vlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log *log, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ea030)
Location: kernel/bpf/verifier.c:233
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
  - kernel/bpf/btf.c:__btf_verifier_log
```
**Symbols:**

```
ffffffff811ea030-ffffffff811ea123: bpf_verifier_vlog (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
