# Function: <code>parse_crash_elf32_headers</code>

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
In fs/proc/vmcore.c (ffffffff81f91841)
Location: fs/proc/vmcore.c:1055
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
In fs/proc/vmcore.c (ffffffff81fbc1d6)
Location: fs/proc/vmcore.c:1058
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
In fs/proc/vmcore.c (ffffffff81ff8bf0)
Location: fs/proc/vmcore.c:1058
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
In fs/proc/vmcore.c (ffffffff820dbc7d)
Location: fs/proc/vmcore.c:1058
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
In fs/proc/vmcore.c (ffffffff826e4912)
Location: fs/proc/vmcore.c:1058
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
In fs/proc/vmcore.c (ffffffff8270ef12)
Location: fs/proc/vmcore.c:1217
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
In fs/proc/vmcore.c (ffffffff828c6096)
Location: fs/proc/vmcore.c:1239
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
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828df2d1)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828df2d1-ffffffff828df750: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e7caf)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828e7caf-ffffffff828e8127: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82d02821)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf_headers
```
**Symbols:**

```
ffffffff82d02821-ffffffff82d02a49: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82fefb1a)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf_headers
```
**Symbols:**

```
ffffffff82fefb1a-ffffffff82fefd4c: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff831fa3cc)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff831fa3cc-ffffffff831fa60f: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff832e12fc)
Location: fs/proc/vmcore.c:1248
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff832e12fc-ffffffff832e154c: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff834973fb)
Location: fs/proc/vmcore.c:1266
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff834973fb-ffffffff83497665: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83ecc8c0)
Location: fs/proc/vmcore.c:1265
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff83ecc8c0-ffffffff83eccb8d: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff836f1940)
Location: fs/proc/vmcore.c:1264
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff836f1940-ffffffff836f1c0d: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83924a20)
Location: fs/proc/vmcore.c:1264
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff83924a20-ffffffff83924d19: parse_crash_elf32_headers (STB_LOCAL)
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
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffff800011461874)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffff800011461874-ffff800011461cfc: parse_crash_elf32_headers (STB_LOCAL)
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
In fs/proc/vmcore.c (c153998c)
Location: fs/proc/vmcore.c:1244
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
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c00000000138d3f4)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
c00000000138d3f4-c00000000138d968: parse_crash_elf32_headers (STB_LOCAL)
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
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828d0b63)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828d0b63-ffffffff828d0fdb: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828c927f)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828c927f-ffffffff828c96f7: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e38e3)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828e38e3-ffffffff828e3d5b: parse_crash_elf32_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_crash_elf32_headers();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e8cf9)
Location: fs/proc/vmcore.c:1244
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff828e8cf9-ffffffff828e9171: parse_crash_elf32_headers (STB_LOCAL)
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
