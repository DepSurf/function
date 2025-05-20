# Function: <code>module_find_bug</code>

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
In lib/bug.c (ffffffff813e8c24)
Location: lib/bug.c:64
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
In lib/bug.c (ffffffff8142ee94)
Location: lib/bug.c:64
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
In lib/bug.c (ffffffff8144b004)
Location: lib/bug.c:64
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
In lib/bug.c (ffffffff818eb274)
Location: lib/bug.c:65
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
In lib/bug.c (ffffffff819711b4)
Location: lib/bug.c:66
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff819cd570)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff819cd570-ffffffff819cd5e2: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a068d0)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a068d0-ffffffff81a06942: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a76240)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a76240-ffffffff81a762ad: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81aad640)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81aad640-ffffffff81aad6ad: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff815e7844)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8160ca04)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff815efcc7)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8165cdd7)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8177618b)
Location: lib/bug.c:66
Inline: True
Inline callers:
  - lib/bug.c:find_bug
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
In lib/bug.c (ffffffff8201eacb)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
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
In lib/bug.c (ffffffff8209eaf3)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
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
In lib/bug.c (ffffffff82176af3)
Location: lib/bug.c:67
Inline: True
Inline callers:
  - lib/bug.c:find_bug
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
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffff800010d838d0)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffff800010d838d0-ffff800010d83950: module_find_bug (STB_LOCAL)
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
In lib/bug.c (c0e7ebe4)
Location: lib/bug.c:66
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bug.c (c000000000ec2428)
Location: lib/bug.c:66
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffe0008adf44)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffe0008adf44-ffffffe0008adfaa: module_find_bug (STB_LOCAL)
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
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a4c490)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a4c490-ffffffff81a4c4fd: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a095c0)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a095c0-ffffffff81a0962d: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81ab8880)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81ab8880-ffffffff81ab88ed: module_find_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bug_entry *module_find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81ac4c90)
Location: lib/bug.c:66
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81ac4c90-ffffffff81ac4d18: module_find_bug (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
