# Function: <code>time64_to_tm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81100b50)
Location: kernel/time/timeconv.c:77
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_time_unix2fat
```
**Symbols:**

```
ffffffff81100b50-ffffffff81100f24: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff811038f0)
Location: kernel/time/timeconv.c:77
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_time_unix2fat
```
**Symbols:**

```
ffffffff811038f0-ffffffff81103cc4: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81105a20)
Location: kernel/time/timeconv.c:77
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_time_unix2fat
```
**Symbols:**

```
ffffffff81105a20-ffffffff81105dec: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81110a90)
Location: kernel/time/timeconv.c:77
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff81110a90-ffffffff81110e5c: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff8111c4a0)
Location: kernel/time/timeconv.c:77
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff8111c4a0-ffffffff8111c858: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81127c50)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff81127c50-ffffffff81128008: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81132670)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff81132670-ffffffff81132a46: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff8113e5c0)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff8113e5c0-ffffffff8113e996: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff8114d7f0)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8114d7f0-ffffffff8114dbb8: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81149940)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff81149940-ffffffff81149d08: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff8114ae10)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8114ae10-ffffffff8114b1da: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff8116ec80)
Location: kernel/time/timeconv.c:47
Inline: False
Direct callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8116ec80-ffffffff8116ee57: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff811a2fa0)
Location: kernel/time/timeconv.c:47
Inline: False
Direct callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff811a2fa0-ffffffff811a3198: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff811e2560)
Location: kernel/time/timeconv.c:47
Inline: False
Direct callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff811e2560-ffffffff811e2758: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff811f6ac0)
Location: kernel/time/timeconv.c:47
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff811f6ac0-ffffffff811f6d4b: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff8120cc60)
Location: kernel/time/timeconv.c:47
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8120cc60-ffffffff8120ceeb: time64_to_tm (STB_GLOBAL)
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffff8000101a82d0)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
**Symbols:**

```
ffff8000101a82d0-ffff8000101a86c8: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (c03f36d8)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
c03f36d8-c03f3a30: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (c00000000020b1a0)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
c00000000020b1a0-c00000000020b610: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffe0001340e6)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffe0001340e6-ffffffe0001342c4: time64_to_tm (STB_GLOBAL)
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81136d70)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff81136d70-ffffffff81137146: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff811297c0)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff811297c0-ffffffff81129b96: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff81134a90)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff81134a90-ffffffff81134e66: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timeconv.c (ffffffff811414b0)
Location: kernel/time/timeconv.c:78
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/fat/misc.c:fat_time_unix2fat
  - security/tomoyo/util.c:tomoyo_convert_time
```
**Symbols:**

```
ffffffff811414b0-ffffffff81141886: time64_to_tm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
