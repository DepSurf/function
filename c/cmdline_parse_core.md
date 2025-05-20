# Function: <code>cmdline_parse_core</code>

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
In mm/page_alloc.c (ffffffff81f86af0)
Location: mm/page_alloc.c:5741
Inline: True
Inline callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
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
In mm/page_alloc.c (ffffffff81fb07e1)
Location: mm/page_alloc.c:6362
Inline: True
Inline callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
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
In mm/page_alloc.c (ffffffff81feca40)
Location: mm/page_alloc.c:6401
Inline: True
Inline callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
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
In mm/page_alloc.c (ffffffff820ce732)
Location: mm/page_alloc.c:6696
Inline: True
Inline callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
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
In mm/page_alloc.c (ffffffff826d714d)
Location: mm/page_alloc.c:6709
Inline: True
Inline callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82701431)
Location: mm/page_alloc.c:6863
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff82701431-ffffffff827014c2: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b83f4)
Location: mm/page_alloc.c:7170
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828b83f4-ffffffff828b8485: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d54fd)
Location: mm/page_alloc.c:7372
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828d54fd-ffffffff828d55a1: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828dd984)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828dd984-ffffffff828dda15: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfacc0)
Location: mm/page_alloc.c:7433
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff82cfacc0-ffffffff82cfad4f: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe7935)
Location: mm/page_alloc.c:7579
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff82fe7935-ffffffff82fe79c4: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f209c)
Location: mm/page_alloc.c:7797
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff831f209c-ffffffff831f212b: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d7c9f)
Location: mm/page_alloc.c:8039
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff832d7c9f-ffffffff832d7d2e: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348c97b)
Location: mm/page_alloc.c:8225
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff8348c97b-ffffffff8348ca19: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebe2c0)
Location: mm/page_alloc.c:8399
Inline: True
Inline callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
Direct callers:
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff83ebdeb0-ffffffff83ebdf4e: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e06c0)
Location: mm/mm_init.c:235
Inline: True
Inline callers:
  - mm/mm_init.c:cmdline_parse_movablecore
Direct callers:
  - mm/mm_init.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff836e0290-ffffffff836e0334: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83912fc0)
Location: mm/mm_init.c:235
Inline: True
Inline callers:
  - mm/mm_init.c:cmdline_parse_movablecore
Direct callers:
  - mm/mm_init.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff83912b40-ffffffff83912be4: cmdline_parse_core (STB_LOCAL)
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
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800011456698)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffff800011456698-ffff80001145675c: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c00000000137fd1c)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
c00000000137fd1c-c00000000137fdfc: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00001539c)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffe00001539c-ffffffe00001541a: cmdline_parse_core (STB_LOCAL)
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
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c6838)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828c6838-ffffffff828c68c9: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828bef5d)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828bef5d-ffffffff828befee: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d95b8)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828d95b8-ffffffff828d9649: cmdline_parse_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cmdline_parse_core(char *p, long unsigned int *core, long unsigned int *percent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828de9d9)
Location: mm/page_alloc.c:7402
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
```
**Symbols:**

```
ffffffff828de9d9-ffffffff828dea6a: cmdline_parse_core (STB_LOCAL)
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
