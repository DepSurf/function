# Function: <code>do_eventfd</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812eee70)
Location: fs/eventfd.c:383
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff812eee70-ffffffff812eef31: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81303800)
Location: fs/eventfd.c:383
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81303800-ffffffff813038c1: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81324da0)
Location: fs/eventfd.c:391
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81324da0-ffffffff81324e82: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81337b30)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81337b30-ffffffff81337c12: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813716a0)
Location: fs/eventfd.c:404
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff813716a0-ffffffff813717d3: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8137f460)
Location: fs/eventfd.c:407
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff8137f460-ffffffff8137f593: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813860e0)
Location: fs/eventfd.c:407
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff813860e0-ffffffff81386213: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813d33b0)
Location: fs/eventfd.c:405
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff813d33b0-ffffffff813d34e3: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8145c980)
Location: fs/eventfd.c:405
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff8145c980-ffffffff8145cac5: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff814ec060)
Location: fs/eventfd.c:414
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff814ec060-ffffffff814ec1a5: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81523220)
Location: fs/eventfd.c:389
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81523220-ffffffff81523365: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81557920)
Location: fs/eventfd.c:377
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81557920-ffffffff81557a98: do_eventfd (STB_LOCAL)
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
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffff8000103f5db0)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__arm64_sys_eventfd
  - fs/eventfd.c:__arm64_sys_eventfd2
```
**Symbols:**

```
ffff8000103f5db0-ffff8000103f5eb0: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c05cac38)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__se_sys_eventfd
  - fs/eventfd.c:__se_sys_eventfd2
```
**Symbols:**

```
c05cac38-c05cad28: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c0000000004fde40)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__se_sys_eventfd
  - fs/eventfd.c:__se_sys_eventfd2
```
**Symbols:**

```
c0000000004fde40-c0000000004fdfb0: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffe0002a66e2)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__se_sys_eventfd
  - fs/eventfd.c:__se_sys_eventfd2
```
**Symbols:**

```
ffffffe0002a66e2-ffffffe0002a67c8: do_eventfd (STB_LOCAL)
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
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81330110)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81330110-ffffffff813301f2: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81320d30)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff81320d30-ffffffff81320e12: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132dbe0)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff8132dbe0-ffffffff8132dcc2: do_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813409c0)
Location: fs/eventfd.c:406
Inline: False
Direct callers:
  - fs/eventfd.c:__ia32_sys_eventfd
  - fs/eventfd.c:__x64_sys_eventfd
  - fs/eventfd.c:__ia32_sys_eventfd2
  - fs/eventfd.c:__x64_sys_eventfd2
```
**Symbols:**

```
ffffffff813409c0-ffffffff81340aa2: do_eventfd (STB_LOCAL)
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
