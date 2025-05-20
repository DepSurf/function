# Function: <code>kmsg_dump_get_line_nolock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d9d30)
Location: kernel/printk/printk.c:2924
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810d9d30-ffffffff810d9ddd: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810def00)
Location: kernel/printk/printk.c:3066
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810def00-ffffffff810defad: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e5460)
Location: kernel/printk/printk.c:2898
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810e5460-ffffffff810e5519: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e47c0)
Location: kernel/printk/printk.c:2905
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810e47c0-ffffffff810e487a: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eca80)
Location: kernel/printk/printk.c:2899
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810eca80-ffffffff810ecb3a: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4c50)
Location: kernel/printk/printk.c:3076
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810f4c50-ffffffff810f4cf3: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81100400)
Location: kernel/printk/printk.c:3088
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff81100400-ffffffff811004ba: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108be0)
Location: kernel/printk/printk.c:3153
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff81108be0-ffffffff81108c9c: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114fc0)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff81114fc0-ffffffff8111507c: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81120970)
Location: kernel/printk/printk.c:3255
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff81120970-ffffffff81120a2a: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b8f0)
Location: kernel/printk/printk.c:3332
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff8111b8f0-ffffffff8111b9f0: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
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
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010176190)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffff800010176190-ffff800010176290: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c8370)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
c03c8370-c03c8470: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cfc80)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:dump_log_buf
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
c0000000001cfc80-c0000000001cfdac: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe0001117b8)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
```
**Symbols:**

```
ffffffe0001117b8-ffffffe00011188c: kmsg_dump_get_line_nolock (STB_GLOBAL)
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
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110d5a0)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff8110d5a0-ffffffff8110d65c: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe310)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff810fe310-ffffffff810fe3cc: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b490)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff8110b490-ffffffff8110b54c: kmsg_dump_get_line_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kmsg_dump_get_line_nolock(struct kmsg_dumper *dumper, bool syslog, char *line, size_t size, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116950)
Location: kernel/printk/printk.c:3163
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
```
**Symbols:**

```
ffffffff81116950-ffffffff81116a0c: kmsg_dump_get_line_nolock (STB_GLOBAL)
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
