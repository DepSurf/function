# Function: <code>read_into</code>

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
In init/initramfs.c (ffffffff81f5c1ee)
Location: init/initramfs.c:215
Inline: True
Inline callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
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
In init/initramfs.c (ffffffff81f8418f)
Location: init/initramfs.c:215
Inline: True
Inline callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
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
In init/initramfs.c (ffffffff81fbf711)
Location: init/initramfs.c:215
Inline: True
Inline callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
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
In init/initramfs.c (ffffffff8209fe2b)
Location: init/initramfs.c:216
Inline: True
Inline callers:
  - init/initramfs.c:do_start
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
In init/initramfs.c (ffffffff826a5e2b)
Location: init/initramfs.c:217
Inline: True
Inline callers:
  - init/initramfs.c:do_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826ce396)
Location: init/initramfs.c:217
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff826ce396-ffffffff826ce3f1: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff828843d9)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff828843d9-ffffffff82884434: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289b42a)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8289b42a-ffffffff8289b48a: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289e40f)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8289e40f-ffffffff8289e46f: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82cc4920)
Location: init/initramfs.c:208
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff82cc4920-ffffffff82cc4980: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82fb0255)
Location: init/initramfs.c:209
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff82fb0255-ffffffff82fb02b5: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff831ba2b8)
Location: init/initramfs.c:221
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff831ba2b8-ffffffff831ba30f: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8329a776)
Location: init/initramfs.c:222
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8329a776-ffffffff8329a7cd: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83448b05)
Location: init/initramfs.c:245
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff83448b05-ffffffff83448b68: read_into (STB_LOCAL)
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
In init/initramfs.c (ffffffff83e6334f)
Location: init/initramfs.c:245
Inline: True
Inline callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
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
In init/initramfs.c (ffffffff8368396f)
Location: init/initramfs.c:239
Inline: True
Inline callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
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
In init/initramfs.c (ffffffff838b2a7f)
Location: init/initramfs.c:239
Inline: True
Inline callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
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
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffff8000114325c4)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffff8000114325c4-ffff80001143263c: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c1502648)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
c1502648-c15026a4: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c000000001345e08)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
c000000001345e08-c000000001345ea0: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffe0000021c6)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffe0000021c6-ffffffe000002230: read_into (STB_LOCAL)
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
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288c40f)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8288c40f-ffffffff8288c46f: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288a38c)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8288a38c-ffffffff8288a3ec: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289f40f)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8289f40f-ffffffff8289f46f: read_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void read_into(char *buf, unsigned int size, enum state next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289f414)
Location: init/initramfs.c:207
Inline: False
Direct callers:
  - init/initramfs.c:do_header
  - init/initramfs.c:do_start
```
**Symbols:**

```
ffffffff8289f414-ffffffff8289f474: read_into (STB_LOCAL)
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
