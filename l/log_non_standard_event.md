# Function: <code>log_non_standard_event</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void log_non_standard_event(const uuid_le *sec_type, const uuid_le *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff817a4990)
Location: drivers/ras/ras.c:16
Inline: False
```
**Symbols:**

```
ffffffff817a4990-ffffffff817a4a20: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void log_non_standard_event(const uuid_le *sec_type, const uuid_le *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff8181bac0)
Location: drivers/ras/ras.c:17
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
**Symbols:**

```
ffffffff8181bac0-ffffffff8181bb5d: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void log_non_standard_event(const uuid_le *sec_type, const uuid_le *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81865bb0)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81865bb0-ffffffff81865c4d: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void log_non_standard_event(const uuid_le *sec_type, const uuid_le *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81885780)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81885780-ffffffff8188581d: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff818cfef0)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff818cfef0-ffffffff818cff84: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819022e0)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff819022e0-ffffffff81902374: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819d9280)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff819d9280-ffffffff819d931d: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819d8630)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff819d8630-ffffffff819d8681: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819be7b0)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff819be7b0-ffffffff819be801: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81a6dd60)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81a6dd60-ffffffff81a6ddae: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81bdeb00)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81bdeb00-ffffffff81bdebc6: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81d89f50)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81d89f50-ffffffff81d8a016: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81df8550)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81df8550-ffffffff81df8616: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81eaec60)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81eaec60-ffffffff81eaed26: log_non_standard_event (STB_GLOBAL)
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
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffff800010b9e350)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffff800010b9e350-ffff800010b9e430: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (c0c8037c)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
c0c8037c-c0c80444: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (c000000000c71360)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
c000000000c71360-c000000000c71464: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffe000736802)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffe000736802-ffffffe0007368a6: log_non_standard_event (STB_GLOBAL)
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
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff818a1710)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff818a1710-ffffffff818a17a4: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff8185ce80)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff8185ce80-ffffffff8185cf14: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff818f2d00)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff818f2d00-ffffffff818f2d94: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void log_non_standard_event(const guid_t *sec_type, const guid_t *fru_id, const char *fru_text, const u8 sev, const u8 *err, const u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81913d80)
Location: drivers/ras/ras.c:17
Inline: False
```
**Symbols:**

```
ffffffff81913d80-ffffffff81913e2b: log_non_standard_event (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
