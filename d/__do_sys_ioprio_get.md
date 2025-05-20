# Function: <code>__do_sys_ioprio_get</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8149a18e)
Location: block/ioprio.c:185
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
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
In block/ioprio.c (ffffffff814b449e)
Location: block/ioprio.c:185
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
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
In block/ioprio.c (ffffffff814e29be)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
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
In block/ioprio.c (ffffffff814fbd7e)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8155b9f0)
Location: block/ioprio.c:186
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff8155b9f0-ffffffff8155bd11: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81577b50)
Location: block/ioprio.c:186
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff81577b50-ffffffff81577e65: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8157f890)
Location: block/ioprio.c:193
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff8157f890-ffffffff8157fba5: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff815e4b30)
Location: block/ioprio.c:199
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff815e4b30-ffffffff815e4e84: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81693b00)
Location: block/ioprio.c:167
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff81693b00-ffffffff81693ef4: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81752b30)
Location: block/ioprio.c:209
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff81752b30-ffffffff81752e9b: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8178ed00)
Location: block/ioprio.c:210
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff8178ed00-ffffffff8178f063: __do_sys_ioprio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_ioprio_get(int which, int who);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff817d1630)
Location: block/ioprio.c:184
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff817d1630-ffffffff817d194b: __do_sys_ioprio_get (STB_LOCAL)
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
In block/ioprio.c (ffff8000105fddf0)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__arm64_sys_ioprio_get
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
In block/ioprio.c (c07a8ff0)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
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
In block/ioprio.c (c0000000007978d8)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffe000439a66)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
```
</details>
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
In block/ioprio.c (ffffffff814f435e)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
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
In block/ioprio.c (ffffffff814e486e)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
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
In block/ioprio.c (ffffffff814f03ee)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
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
In block/ioprio.c (ffffffff8150948e)
Location: block/ioprio.c:186
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
