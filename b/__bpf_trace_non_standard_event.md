# Function: <code>__bpf_trace_non_standard_event</code>

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
void __bpf_trace_non_standard_event(void *__data, const uuid_le *sec_type, const uuid_le *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81864ba0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81864ba0-ffffffff81864bb4: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const uuid_le *sec_type, const uuid_le *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81884770)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81884770-ffffffff81884784: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff818cee60)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff818cee60-ffffffff818cee74: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81901250)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81901250-ffffffff81901264: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819d8280)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff819d8280-ffffffff819d8294: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819d7630)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff819d7630-ffffffff819d7644: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819bd7a0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff819bd7a0-ffffffff819bd7b4: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81a6cd50)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81a6cd50-ffffffff81a6cd64: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81bddbe0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81bddbe0-ffffffff81bddc08: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81d88f80)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81d88f80-ffffffff81d88fa8: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81df7590)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81df7590-ffffffff81df75b8: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81eadca0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81eadca0-ffffffff81eadcc8: __bpf_trace_non_standard_event (STB_LOCAL)
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
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffff800010b9d500)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffff800010b9d500-ffff800010b9d51c: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (c0c7f6d8)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
c0c7f6d8-c0c7f734: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (c000000000c701f0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
c000000000c701f0-c000000000c7021c: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff818a09c0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff818a09c0-ffffffff818a09d4: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff8185c130)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff8185c130-ffffffff8185c144: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff818f1c70)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff818f1c70-ffffffff818f1c84: __bpf_trace_non_standard_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_non_standard_event(void *__data, const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81912cf0)
Location: include/ras/ras_event.h:219
Inline: False
```
**Symbols:**

```
ffffffff81912cf0-ffffffff81912d04: __bpf_trace_non_standard_event (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const uuid_le *sec_type</code> ➡️ <code>const guid_t *sec_type</code>
</li>
<li>
<b>Param type changed. </b>
<code>const uuid_le *fru_id</code> ➡️ <code>const guid_t *fru_id</code>
</li>
</ul>
</details>
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
