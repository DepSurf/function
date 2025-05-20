# Function: <code>parse_crash_elf64_headers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81f9165e)
Location: fs/proc/vmcore.c:999
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81fbbfd8)
Location: fs/proc/vmcore.c:1002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81ff89f2)
Location: fs/proc/vmcore.c:1002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff820dba9d)
Location: fs/proc/vmcore.c:1002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff826e4732)
Location: fs/proc/vmcore.c:1002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8270ed5a)
Location: fs/proc/vmcore.c:1161
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828c5ec9)
Location: fs/proc/vmcore.c:1183
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828dee56)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828dee56-ffffffff828df2d1: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e782e)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828e782e-ffffffff828e7caf: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82d022ee)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf_headers
```
**Symbols:**

```
ffffffff82d022ee-ffffffff82d02528: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82fef5dd)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf_headers
```
**Symbols:**

```
ffffffff82fef5dd-ffffffff82fef821: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff831f9e8e)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff831f9e8e-ffffffff831fa0d3: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff832e0db7)
Location: fs/proc/vmcore.c:1192
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff832e0db7-ffffffff832e1003: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83496e61)
Location: fs/proc/vmcore.c:1210
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff83496e61-ffffffff834970cb: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83ecc1b0)
Location: fs/proc/vmcore.c:1209
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff83ecc1b0-ffffffff83ecc480: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff836f1230)
Location: fs/proc/vmcore.c:1208
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff836f1230-ffffffff836f14fa: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff839242d0)
Location: fs/proc/vmcore.c:1208
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff839242d0-ffffffff839245d2: parse_crash_elf64_headers (STB_LOCAL)
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
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffff8000114613e8)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffff8000114613e8-ffff800011461874: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c1539960)
Location: fs/proc/vmcore.c:1188
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c00000000138ce70)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
c00000000138ce70-c00000000138d3f4: parse_crash_elf64_headers (STB_LOCAL)
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
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828d06e2)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828d06e2-ffffffff828d0b63: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828c8dfe)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828c8dfe-ffffffff828c927f: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e3462)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828e3462-ffffffff828e38e3: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_crash_elf64_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e8878)
Location: fs/proc/vmcore.c:1188
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828e8878-ffffffff828e8cf9: parse_crash_elf64_headers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
