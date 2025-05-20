# Function: <code>seq_vprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230eb0)
Location: fs/seq_file.c:395
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff81230eb0-ffffffff81230efb: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812591c0)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff812591c0-ffffffff8125920b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c670)
Location: fs/seq_file.c:405
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff8126c670-ffffffff8126c6bb: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a230)
Location: fs/seq_file.c:391
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff8127a230-ffffffff8127a27b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129ccb0)
Location: fs/seq_file.c:395
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff8129ccb0-ffffffff8129ccfb: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c2dd0)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff812c2dd0-ffffffff812c2e1b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7d40)
Location: fs/seq_file.c:386
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff812d7d40-ffffffff812d7d8b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6250)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff812f6250-ffffffff812f629b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81307e20)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff81307e20-ffffffff81307e6b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134201a)
Location: fs/seq_file.c:374
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
```
**Symbols:**

```
ffffffff81341300-ffffffff81341353: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e6da)
Location: fs/seq_file.c:390
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
```
**Symbols:**

```
ffffffff8134d370-ffffffff8134d3c3: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81354a33)
Location: fs/seq_file.c:393
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
```
**Symbols:**

```
ffffffff81353f70-ffffffff81353fc6: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2e43)
Location: fs/seq_file.c:402
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
  - mm/kfence/report.c:seq_con_printf
```
**Symbols:**

```
ffffffff813a23a0-ffffffff813a23f6: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81426b94)
Location: fs/seq_file.c:386
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
  - mm/kfence/report.c:seq_con_printf
```
**Symbols:**

```
ffffffff81425f40-ffffffff81425faf: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3624)
Location: fs/seq_file.c:386
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
  - mm/kfence/report.c:seq_con_printf
```
**Symbols:**

```
ffffffff814b2830-ffffffff814b289f: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e8694)
Location: fs/seq_file.c:386
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
  - mm/kfence/report.c:seq_con_printf
```
**Symbols:**

```
ffffffff814e7880-ffffffff814e78ef: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151c524)
Location: fs/seq_file.c:386
Inline: True
Inline callers:
  - fs/seq_file.c:seq_printf
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - kernel/bpf/btf.c:btf_seq_show
  - mm/kfence/report.c:seq_con_printf
```
**Symbols:**

```
ffffffff8151b710-ffffffff8151b77f: seq_vprintf (STB_GLOBAL)
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
void seq_vprintf(struct seq_file *m, const char *f, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bb8f8)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffff8000103bb8f8-ffff8000103bb990: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0599110)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
c0599110-c0599174: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b8d50)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
c0000000004b8d50-c0000000004b8dfc: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d422)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffe00027d422-ffffffe00027d484: seq_vprintf (STB_GLOBAL)
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
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300400)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff81300400-ffffffff8130044b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f1020)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff812f1020-ffffffff812f106b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe1f0)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff812fe1f0-ffffffff812fe23b: seq_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void seq_vprintf(struct seq_file *m, const char *f, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f530)
Location: fs/seq_file.c:398
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/seq_file.c:seq_printf
```
**Symbols:**

```
ffffffff8130f530-ffffffff8130f57b: seq_vprintf (STB_GLOBAL)
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
