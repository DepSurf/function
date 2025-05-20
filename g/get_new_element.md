# Function: <code>get_new_element</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81f910a7)
Location: fs/proc/vmcore.c:497
Inline: False
```
**Symbols:**

```
ffffffff81f910a7-ffffffff81f910c3: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81fbba15)
Location: fs/proc/vmcore.c:500
Inline: False
```
**Symbols:**

```
ffffffff81fbba15-ffffffff81fbba31: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81ff842f)
Location: fs/proc/vmcore.c:500
Inline: False
```
**Symbols:**

```
ffffffff81ff842f-ffffffff81ff844b: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff820db4d8)
Location: fs/proc/vmcore.c:500
Inline: False
```
**Symbols:**

```
ffffffff820db4d8-ffffffff820db4f9: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff826e416d)
Location: fs/proc/vmcore.c:500
Inline: False
```
**Symbols:**

```
ffffffff826e416d-ffffffff826e418e: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8270e74e)
Location: fs/proc/vmcore.c:649
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff8270e74e-ffffffff8270e76f: get_new_element (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff828c601c)
Location: fs/proc/vmcore.c:671
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828df68e)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e8084)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82d01fca)
Location: fs/proc/vmcore.c:676
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff82d01fca-ffffffff82d01feb: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82fef2b9)
Location: fs/proc/vmcore.c:676
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff82fef2b9-ffffffff82fef2da: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff831f9b6a)
Location: fs/proc/vmcore.c:676
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff831f9b6a-ffffffff831f9b8b: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff832e0a93)
Location: fs/proc/vmcore.c:680
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff832e0a93-ffffffff832e0ab4: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83496afe)
Location: fs/proc/vmcore.c:698
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff83496afe-ffffffff83496b29: get_new_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83eccad0)
Location: fs/proc/vmcore.c:697
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff836f1b50)
Location: fs/proc/vmcore.c:696
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83924c2c)
Location: fs/proc/vmcore.c:696
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffff800011461c4c)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
In fs/proc/vmcore.c (c1539b58)
Location: fs/proc/vmcore.c:676
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
struct vmcore *get_new_element();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c00000000138ce28)
Location: fs/proc/vmcore.c:676
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
c00000000138ce28-c00000000138ce70: get_new_element (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828d0f38)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828c9654)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e3cb8)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e90ce)
Location: fs/proc/vmcore.c:676
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
</ul>
<b>Arch</b>
<ul>
</ul>
