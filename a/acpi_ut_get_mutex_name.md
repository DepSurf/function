# Function: <code>acpi_ut_get_mutex_name</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8158249c)
Location: drivers/acpi/acpica/utdecode.c:426
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8158249c-ffffffff815824bd: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815b9651)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815b9651-ffffffff815b9672: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815d2a22)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815d2a22-ffffffff815d2a43: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81604323)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81604323-ffffffff81604344: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816257cd)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816257cd-ffffffff816257ee: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1f6b)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816d1f6b-ffffffff816d1f8c: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816eff49)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816eff49-ffffffff816eff6a: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1dae)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816d1dae-ffffffff816d1dcf: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81749568)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81749568-ffffffff8174959d: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8187b8f3)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8187b8f3-ffffffff8187b938: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff819beb40)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff819beb40-ffffffff819beb8a: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a05d30)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81a05d30-ffffffff81a05d7a: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a50bd0)
Location: drivers/acpi/acpica/utdecode.c:388
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81a50bd0-ffffffff81a50c1a: acpi_ut_get_mutex_name (STB_GLOBAL)
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
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffff80001079b1b8)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
**Symbols:**

```
ffff80001079b1b8-ffff80001079b200: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815fe605)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
**Symbols:**

```
ffffffff815fe605-ffffffff815fe626: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815e9afc)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
**Symbols:**

```
ffffffff815e9afc-ffffffff815e9b1d: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81619aad)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81619aad-ffffffff81619ace: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *acpi_ut_get_mutex_name(u32 mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8163395d)
Location: drivers/acpi/acpica/utdecode.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8163395d-ffffffff8163397e: acpi_ut_get_mutex_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
