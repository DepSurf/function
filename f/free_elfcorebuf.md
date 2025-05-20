# Function: <code>free_elfcorebuf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812874f0)
Location: fs/proc/vmcore.c:991
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
```
**Symbols:**

```
ffffffff812874f0-ffffffff81287544: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812b47d0)
Location: fs/proc/vmcore.c:994
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
```
**Symbols:**

```
ffffffff812b47d0-ffffffff812b4824: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812ca060)
Location: fs/proc/vmcore.c:994
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
```
**Symbols:**

```
ffffffff812ca060-ffffffff812ca0b4: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812d7520)
Location: fs/proc/vmcore.c:994
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
```
**Symbols:**

```
ffffffff812d7520-ffffffff812d7574: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812fbc00)
Location: fs/proc/vmcore.c:994
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
```
**Symbols:**

```
ffffffff812fbc00-ffffffff812fbc54: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81329530)
Location: fs/proc/vmcore.c:1153
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff81329530-ffffffff81329584: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813407e0)
Location: fs/proc/vmcore.c:1175
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff813407e0-ffffffff81340834: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81368c10)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81368c10-ffffffff81368c64: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81380e70)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81380e70-ffffffff81380ec4: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813cbe9d)
Location: fs/proc/vmcore.c:1180
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_cleanup
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff813cb350-ffffffff813cb397: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813dcff0)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff813dcff0-ffffffff813dd044: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813e3ee0)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff813e3ee0-ffffffff813e3f34: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff814358e0)
Location: fs/proc/vmcore.c:1184
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff814358e0-ffffffff81435934: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff814afb90)
Location: fs/proc/vmcore.c:1202
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff814afb90-ffffffff814afbee: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81546350)
Location: fs/proc/vmcore.c:1201
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81546350-ffffffff815463ae: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8157df10)
Location: fs/proc/vmcore.c:1200
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff8157df10-ffffffff8157df6e: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815b6950)
Location: fs/proc/vmcore.c:1200
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff815b6950-ffffffff815b69ae: free_elfcorebuf (STB_LOCAL)
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
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffff80001044ec70)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffff80001044ec70-ffff80001044ecd0: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c0611f88)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
c0611f88-c0611fd8: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c000000000566860)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
c000000000566860-c0000000005668ec: free_elfcorebuf (STB_LOCAL)
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
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81379450)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81379450-ffffffff813794a4: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81369f20)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81369f20-ffffffff81369f74: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81376f20)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81376f20-ffffffff81376f74: free_elfcorebuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_elfcorebuf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8138a9d0)
Location: fs/proc/vmcore.c:1180
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff8138a9d0-ffffffff8138aa24: free_elfcorebuf (STB_LOCAL)
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
