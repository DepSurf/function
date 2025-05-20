# Function: <code>__do_sys_ioprio_set</code>

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
In block/ioprio.c (ffffffff8149aa82)
Location: block/ioprio.c:93
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
In block/ioprio.c (ffffffff814b4d92)
Location: block/ioprio.c:93
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
In block/ioprio.c (ffffffff814e3032)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
In block/ioprio.c (ffffffff814fc3f2)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8155bdd0)
Location: block/ioprio.c:94
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff8155bdd0-ffffffff8155c083: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81577f30)
Location: block/ioprio.c:94
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff81577f30-ffffffff815781e4: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8157fc70)
Location: block/ioprio.c:94
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff8157fc70-ffffffff8157ff65: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff815e4f50)
Location: block/ioprio.c:100
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff815e4f50-ffffffff815e5245: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81693fc0)
Location: block/ioprio.c:68
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff81693fc0-ffffffff816942ae: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81752fa0)
Location: block/ioprio.c:68
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff81752fa0-ffffffff8175328e: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8178f170)
Location: block/ioprio.c:69
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff8178f170-ffffffff8178f44c: __do_sys_ioprio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_ioprio_set(int which, int who, int ioprio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff817d1a50)
Location: block/ioprio.c:69
Inline: False
Direct callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff817d1a50-ffffffff817d1d2c: __do_sys_ioprio_set (STB_LOCAL)
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
In block/ioprio.c (ffff8000105fe184)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__arm64_sys_ioprio_set
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
In block/ioprio.c (c07a8d34)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_set
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
In block/ioprio.c (c000000000797db8)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_set
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
In block/ioprio.c (ffffffe000439862)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_set
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
In block/ioprio.c (ffffffff814f49d2)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
In block/ioprio.c (ffffffff814e4ee2)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
In block/ioprio.c (ffffffff814f0a62)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
In block/ioprio.c (ffffffff81509b02)
Location: block/ioprio.c:94
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
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
